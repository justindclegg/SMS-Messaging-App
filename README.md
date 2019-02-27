# SMS-Messaging-App
A web powered SMS Messaging app you can use with a Twilio number

This is an implementation of an SMS Messages app that you can use with a Twilio number.

Warning
This is a work in progress as there are plenty of features to add. Currently the application does the following:

Lists messages sent to your Twilio number (inbox)
Lists messages sent from your Twilio number (outbox)
Conversation view of messages between your Twilio number and another number
Reply to a conversation
Create a new message to a new recipient
Getting started
Clone the repository and install dependencies:

$ git clone https://github.com/philnash/sms-messages-app.git
$ cd sms-messages-app
$ npm install
Copy .env.example to .env and fill in the your Twilio account credentials and the Twilio number you want to use. You can find your Account SID and Auth Token in your Twilio account portal.

$ cp .env.example .env
Then start the application:

$ npm start
Navigate to http://localhost:3000 and you will see the application.
