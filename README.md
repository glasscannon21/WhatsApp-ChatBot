# WhatsApp-ChatBot
WhatsApp ChatBot using DialogFlow and WhatsApp AutoResponder

# Introduction
This is not a DialogFlow tutorial but rather an effort to build an intelligent ChatBot using DialogFlow's AI and Integrating into existing WhatsApp account through Autoresponder, a third party Paid Application avialable on Play Store.

![image](https://github.com/glasscannon21/WhatsApp-ChatBot/blob/master/images/6.jpg)

# 1. Creating the .json key from DialogFlow Agent

1.1 After creating the agents with indents click on the settings and hover to "Google Project" section and click on "service account"

![image](https://github.com/glasscannon21/WhatsApp-ChatBot/blob/master/images/1.png)

1.2 You'll be redirected to "Service Accounts" section of "Google Cloud Platform". Click on "Create service account" on the top of tha page.

![image](https://github.com/glasscannon21/WhatsApp-ChatBot/blob/master/images/2.png)

1.3 type in any name and description and click on "Create" button.

![image](https://github.com/glasscannon21/WhatsApp-ChatBot/blob/master/images/3.png)

1.3 Select "Role" as "DialogFlow API Client" and click "Continue"

![image](https://github.com/glasscannon21/WhatsApp-ChatBot/blob/master/images/4.png)

1.4 Click on "Create keys" and select "JSON" from the two options available. 

![image](https://github.com/glasscannon21/WhatsApp-ChatBot/blob/master/images/5.png)

# 2. Setting up Autoresponder

2.1 Open Autoresponder and click on the "+" sign at the bottom right corner to add a rule for incoming messages

![image](https://github.com/glasscannon21/WhatsApp-ChatBot/blob/master/images/7.jpg)

2.2 Fill in asterisk in the "should be answered" section and select "Process messages with DialogFlow.com" in the settings given

![image](https://github.com/glasscannon21/WhatsApp-ChatBot/blob/master/images/8.jpg)

2.3 Import the .json generated from the DialogFlow and test the ChatBot.

# I have attached with the project a working .json key for a Sample ChatBot derived through the same process, which assists user to order Coffee from a local shop. It doesn't actually orders it, but it's fun to interact with. 

# Hope this helps, I am not able to attach images through custom payload though, If anyone finds this out please let me know. Thanks. 
