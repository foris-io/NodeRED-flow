# NodeRED-flow

This is the NodeRED flow of this project. 

NodeRED retrieves the data from Link-Lab cloud using their REST endpoints.  

Services provided by the NodeRED are as follows.

1. Identifies the speech text of the end user who is interacting with the mobile app. based on the text 
  a. Serves the real-time sensor data to the mobile app 
  b. Serves the real-time weather using weather APIs
 
2. It provides two unique REST end points to the web app. 
  a. Serves the most recent 100 sensors values along with other necessary values as a JSON string. 
  b. Serves the most recent sensor value along with other necessary values as a JSON string. 
  
3. Tring to integrate with Twilio app to push the message to the end user with timely irrigation information. 
  --This phase is still under development. 




Web folder has the exported code of the NodeRED flow. 




![myimage-alt-tag](https://github.com/foris-io/NodeRED-flow/blob/master/images/NodeRED_flow.PNG)
