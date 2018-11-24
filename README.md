![alt text][logo]

[logo]: https://www.outlookseries.com/vendor_perspective/SAP_Af1.jpg "Logo Title Text 2"
# Welcome to SAP Junction Challenge 
## AI-driven customer interactions
Create a concept and a working demo of “an amazing customer experience” in the area of AI-driven customer interactions by using latest AI and other enabling technologies to help businesses communicate and interact smarter with their customers.

### Here is some food for thought for possible use cases or real-world challenges:

* How to help people with different language skills to communicate using chat.
* How voice utilization can help to interact with a chatbot or chat-enabled agent.
* How to derive insights from the dialogs to analyze customer satisfaction.
* Creative ways to use real-time video stream in customer service.
* How to use AI to help customer service agent to provide better answers.
* Can your solution use augmented reality to impress the customer and help in making buying decisions?

## :exclamation: Join our  [**Slack channel**](https://junction2018attendees.slack.com/messages/CDX0L2V29/details/)



---

## Access to SAP software and documentation

Every team will get an access to **Agent Desktop** software which provides the means to communicate via text chat, phone call or video chat. In addition, you will be able to navigate to the **Visitor client** application in order to simulate the real world scenarios when a customer interacts with a customer service.

For example you might want to send a text chat request and have a discussion between an agent and a customer, create a phone call or establish a video stream. To be able to interact with the video/audio streams, chat messages you will provided with the API documentation of **SAP commlib library**.

### **Note about the challenge**

Even though the software and APIs are provided, we are not restricting you to work with them. The purpose is to give the participants a clear understanding of how software works and what the scenarios are.

Feel free to use any tools and technologies to build a fantastic AI solution. We will be helping you to test your ideas with our system.


---

## Setting up Agent desktop, agent users and queues for teams

### :exclamation: This section requires SAP mentors' support. We will help with all the steps in order to configure the system.

Every team will get credentials for 2 agent users and will be assigned to queues.

After receiving the credentials you will be able to access Agent Desktop software, Visitor Client and various agent configurations.

In order to start the experimenting with the software you will need to deploy the Agent Desktop code to your own server. For example you could use popular cloud solutions like [Heroku](https://www.heroku.com/) or [AWS](https://aws.amazon.com/).

We provided an example in this repository. Navigate to [**agent-desktop-example-setup**](./agent-desktop-example-setup) and check out the Express based web server which simply serves static content from the public folder.

The contents and of the public folder will be explained in detail during the workshop on Saturday.

In addition to your own server you will need to configure a destination service in SAP cloud platform. Don't worry, we will provide all the instructions after you configure your own server.


---
## Agent Desktop

Agent Desktop allows you to receive text chats, make phone calls and interact with video chat. Go to [**Agent Desktop**](https://demo01.servicecloud.cfapps.eu10.hana.ondemand.com/sites#EngagementContext-Display)

We will provide more information on how to make phone calls, in case you want to make some AI utilising audio stream like speech to text processing.

---

## Visitor client

From Visitor client you will be able to simulate a customer interaction to the customer support system. Video chat or text chat are available. Go to [**Visitor client**](https://demo01.servicecloud.cfapps.eu10.hana.ondemand.com/visitor-config-ui/)



---

## Commlib API docs

The commlib API is used to subscribe to communication events happening between the customer and the agent. For example you can use it to detect the following things:

* A new phone call is incoming
* A new chat offer is sent
* A new chat message is sent
* Access the video/audio streams from a phone call or a video chat
* An interaction has ended

The full list of events will be provided as well as the documentation of the full API. We will provide more details on how to use APIs during the workshop on Saturday.


### Note 

You might want to try to play with the API and understand how to intercept chat messages, access video/audio stream and then do anything what comes to your mind. For instance, you may send messages to some translation service to enable multilanguage communication, train neural networks to do something with the video or audio streams. Refer to the food for thoughts section on the top.


Feel free to ask for help from SAP mentors at any time.
## :sunglasses: Good luck and happy Hacking! :metal:
