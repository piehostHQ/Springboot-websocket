# WebSocket Demo Project

This is a simple WebSocket demo project that implements real-time communication between a WebSocket server (Spring Boot) and a WebSocket client (HTML + JavaScript). The client can connect to the server, send messages, and receive real-time responses.

---

## **Features**

- Establish a WebSocket connection between the client and server.
- Send and receive messages in real-time.
- Clean UI for testing WebSocket functionality.
- Built-in logging for connection, messages, and disconnection events.

---

## **Technologies Used**

- **Backend**: Spring Boot with WebSocket support.
- **Frontend**: HTML, JavaScript, and CSS.

---

## **Setup and Usage**

### Prerequisites

- Java 11 or higher
- Gradle
- A modern web browser (e.g., Chrome, Firefox)

---

### **1. Clone the Repository**

```bash
git clone https://github.com/piehostHQ/Springboot-websocket.git
cd websocket-demo
```
Navigate to the backend project folder.
Run the Spring Boot application:
```bash
./gradlew bootRun\
```
The WebSocket server will start on http://localhost:8080.

Open the WebSocketClient.html file in a browser.
Use the UI to:
Connect to the server.
Send messages.
View server responses in real-time.
