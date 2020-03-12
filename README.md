# messagingService_Demo

Test out a Messaging Service using this Node.js Twilo Demo packet

Steps to go live: 
Update you Environment Variables to include: 
"ACCOUNT_SID" and "AUTH_TOKEN" variable declaration ( with your own Account SID and AUTH_TOKEN, available in Console)

Git Clone this gitHub file and run the following terminal commands: 

Run npm install
Start server on app.js 

Check Routes for testing various functions, for example: 
Hit the /testCreateMgService enpoint to create a messaging service
Then get the Mg Sid from your console and enter it into line 19 of services.js
Then hit /testBuyPhoneNumbers

You can change the area code and number count on line 18 of api.js

Add a friendlyName to line 7 of service.js
