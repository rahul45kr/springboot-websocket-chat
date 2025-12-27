<img width="1366" height="768" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/4fb94634-e417-4920-be2b-403541c9c295" />


<img width="1366" height="768" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/125d5a47-9384-4319-bf33-8e57152e9e47" />
💬 Real-Time Chat Application using Spring Boot & WebSocket

A real-time chat application built using Spring Boot and WebSocket (STOMP protocol) that enables instant, bi-directional communication between multiple users without page refresh.

🚀 Features

Real-time message exchange

WebSocket-based full-duplex communication

STOMP messaging protocol

Simple and responsive chat UI

No page refresh required

In-memory message handling (can be extended with DB)

🛠️ Tech Stack

Backend: Java, Spring Boot

Real-Time Communication: WebSocket, STOMP

Frontend: HTML, CSS, JavaScript

Build Tool: Maven

IDE: IntelliJ IDEA

🔄 How It Works

Client connects to the WebSocket endpoint /ws

Messages are sent to /app/chat

Server broadcasts messages to subscribed clients on /topic/messages

Communication happens instantly using WebSocket instead of HTTP

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/rahul45kr/springboot-websocket-chat.git

Open the project in IntelliJ IDEA

Run the Spring Boot application

Open browser and visit:
http://localhost:8080/chat
Open multiple tabs to test real-time chat 🚀
