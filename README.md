Real-Time Chat Application
This is a simple real-time chat application built with:

Spring Boot (WebSocket, STOMP, SockJS)

Thymeleaf

Java 17

Bootstrap

📌 Features
✅ Real-time messaging
✅ Multiple user support
✅ WebSocket + STOMP integration
✅ SockJS fallback for browser compatibility
✅ Clean UI with Bootstrap

💻 Technologies Used
Technology	Purpose
Spring Boot	Backend framework
WebSocket + STOMP	Real-time communication protocol
SockJS	WebSocket fallback support
Thymeleaf	Server-side HTML rendering
Bootstrap	UI styling
Lombok	Model boilerplate reduction


Or use term

Navigate to http://localhost:8080/chat in your browser.

📂 Project Structure
com.chat
 ┣ config
 ┃ ┗ WebSocketConfig.java
 ┣ controller
 ┃ ┗ ChatController.java
 ┣ model
 ┃ ┗ ChatMessage.java
 ┣ resources/templates
 ┃ ┗ chat.html
⚙️ Main Files Explanation
WebSocketConfig.java
Configures STOMP endpoints and message broker.

ChatController.java
Handles message mapping and page routing.

ChatMessage.java
Model class for chat messages (sender, content).

chat.html
Frontend UI with SockJS + STOMP client connection and message rendering.
