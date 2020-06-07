# WhatsApp-ChatBot
WhatsApp ChatBot using DialogFlow and WhatsApp AutoResponder

# Introduction
This is not a DialogFlow tutorial but rather an effort to build an intelligent ChatBot using DialogFlow's AI and Integrating into existing WhatsApp account through Autoresponder, a third party Paid Application avialable on Play Store.

(Autoresponder image)

# 1. Creating the .json key from DialogFlow Agent

1.1 After creating the agents with indents click on the settings and hover to "Google Project" section and click on "service account"

![image](https://github.com/glasscannon21/WhatsApp-ChatBot/blob/master/images/1.png)

1.2 You'll be redirected to "Service Accounts" section of "Google Cloud Platform". Click on "Create service account" on the top of tha page and type in any name and description and click on "Create" button.

(Create Service Account)

1.3 Select "Role" as "DialogFlow API Client" and click "Continue"

(Role)

1.4 Click on "Create keys" and select "JSON" from the two options available. 

(JSON key creation)

# 2. Setting up Autoresponder

2.1 Open Autoresponder and click on the "+" sign at the bottom right corner to add a rule for incoming messages

(Home screen)

2.2 Fill in asterisk in the "should be answered" section and select "Process messages with DialogFlow.com" in the settings given

(Settings)

2.3 Import the .json generated from the DialogFlow and test the ChatBot.

(Wroking)

2.4 I have attached with the project a working .json key for a Sample ChatBot derived through the same process, which assists user to order Coffee from a local shop. It doesn't actually orders it, but it's fun to interact with. 

# Hope this helps, I am not able to attach images through custom payload though, If anyone finds this out please let me know. Thanks. 
