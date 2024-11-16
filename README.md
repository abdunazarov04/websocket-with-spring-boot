_Simple Chat Application_ with WebSocket (Java Spring Boot)
This project is a basic chat application built using WebSocket and Spring Boot. Follow the steps below to set up, build,
and run the application.
---

1. **Install the Project**
   Clone or download the project to your local machine. You can use the following command to clone the repository:

```bash

git clone <https://github.com/abdunazarov04/websocket-with-spring-boot.git>
```

---

2. **Check Java Version**
   Ensure you have the correct Java version installed for this project.

Open the pom.xml file and look for the <java.version> property to verify the required version.
If you're using IntelliJ IDEA:
Navigate to File > **Project Structure** > **SDKs** to ensure the correct **JDK** is selected.
Make sure the selected **JDK** version matches the one specified in the pom.xml.
---

3. Create a Target File
   Use Maven to build the project and create the target file.

Run the following command in the project directory:

```bash

mvn clean package
```

This will clean the project, compile the source code, and package it into a deployable .jar file located in the target
directory.
---

4. Run the Project
   Run the packaged .jar file to start the Spring Boot application.

```bash

java -jar target/<your_project_name>.jar
```

Alternatively, if you are using an IDE like IntelliJ IDEA, you can directly run the application by executing the main
method in the primary Spring Boot class.


---

5. Open the Browser
   Once the application is running, open your browser and go to:

```bash

http://localhost:8080
```

You should now see the chat application interface. Enter a username to start chatting!

````
Features
Real-time communication using WebSocket.
Spring Boot backend for efficient server-side processing.
Dynamic message handling for joining, chatting, and leaving events.

Prerequisites
Java: Ensure the required version is installed.
Maven: To build the project.
Browser: A modern browser for accessing the application.
````