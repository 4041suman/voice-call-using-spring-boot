# voice-call-using-spring-boot
Realtime Chat Application using Spring Boot
Spring MVC is a framework built on top of Java servlets that provides the components needed to build web applications using the model-view-controller architecture. It is one of the many tools provided by the Spring project. The MVC Pattern is a way of separating the logic of a program from the representation. The model does all the heavy stuff like calculate data, work with user input, and save things. The view is what the user sees and interacts with. The controller keeps track of changes in the view (for example a pressed button) and updates the model and the view. These three components work together in Spring MVC to create a dynamic and responsive application.

Twilio is a 3rd party application used to send SMS and make voice calls from our application. It allows us to send the SMS and make voice calls programmatically.

A Twilio account - sign up
Twilio Account Settings
This application should give you a ready-made starting point for writing your own appointment reminder application. Before we begin, we need to collect all the config values we need to run the application:

Config Value	Description
Account Sid	Your primary Twilio account identifier - find this in the Console.
Auth Token	Used to authenticate - just like the above, you'll find this here.
Phone number	A Twilio phone number in E.164 format - you can get one here
For example:

Account SID: ACXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
Call SID:    CAXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
API Key:     SKXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

