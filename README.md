# Spring Boot Tutorial

Spring MVC - blueprint for building web applications in Java. It splits the work into three parts:

Model: Holds your data and rules.

View: Shows the stuff to the user (like web pages).

Controller: Takes user requests, gets data from the Model, and decides what View to show.

# How it works

User Interaction: When a user interacts with your web application (e.g., clicking a link or submitting a form), the request is sent to the Controller.

Controller Processing: The Controller processes the user's request. It may retrieve data from the Model or perform some business logic.

Model Data: The data from the Model is prepared. This could be user information, product details, or any other information that needs to be shown to the user.

View Selection: Based on the result of the Controller's processing and the data from the Model, the Controller selects the appropriate View to display. The View is often an HTML page or a template.

Rendering: The View is then rendered, which means it's converted into the HTML that the user sees. The data from the Model is inserted into the View to generate the final HTML page.

Response: The HTML page is sent as a response to the user's browser, and the user sees the web page on their screen.

# How to run

Ensure IntelliJ is using Command Prompt Terminal. File > Tools > Terminal > Shell Path: cmd.exe

On the terminal type 'mvnw.cmd spring-boot:run'

On your web browser go to http://localhost:8080/myendpoint/

To check health of springboot application go to http://localhost:8080/myendpoint/actuator/health

# Resource
https://spring.io/guides/gs/spring-boot/#scratch
