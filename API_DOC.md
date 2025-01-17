To run locally the code you need SIA_Greennode move app folder outside anywhere on c but I move it in my htdocs
 ![Image](https://github.com/user-attachments/assets/1d8ffee1-8fbf-4fc5-b9cc-3b9cc64f650c)
Go to terminal npm install to install packages 
 ![Image](https://github.com/user-attachments/assets/f430da0d-4d74-4d2b-becd-5116f8c530ed)
Next is npm install twilio
 ![Image](https://github.com/user-attachments/assets/ffc937c7-9624-47d0-9234-4ab56f67dfc4)
Npm start to run
 ![Image](https://github.com/user-attachments/assets/a1eb66f5-2fc8-4010-9ad6-7930598fb128)
Type localhost:3000 to browser
 ![Image](https://github.com/user-attachments/assets/64e3a1fd-ae17-4193-adeb-3b844a1b4b5a)
![Image](https://github.com/user-attachments/assets/67465851-fa88-48a5-b503-c8b4707fa3ce)
 API Endpoints
Send Message
Endpoint: /send-message

Method: POST

Body:  
json  
{
    "sid": "string",
    "sender": "integer",
    "to": "integer",
    "body": "string"
}  
Example Request:  
json  
{
    "sid": "msg.sid",
    "sender": "msg.from",
    "to": "msg.to",
    "body": "msg.body"
}
Example Response:  

json  
{
    "sid": "SMb3667650c8b87c35b559cc447af170a9",
    "sender": "+12317588838",
    "to": "+639627596868",
    "body": "Sent from your Twilio trial account - Green says: Hello my friend"
}  
Package.json  
 Dependencies: Libraries and packages your project needs to work.
  DevDependencies: Libraries and packages needed only for development.

