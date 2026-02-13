
#  Real-Time Chat Application (Spring Boot + WebSocket)

A real-time chat application built using Spring Boot and WebSocket technology that enables users to send and receive messages instantly through a browser-based interface. This project demonstrates real-time communication using STOMP messaging and topic-based broadcasting.

The application is simple, readable, and structured like a real backend project.

---

##  Features

- Real-time chat using WebSockets  
- Instant message broadcasting  
- STOMP messaging protocol  
- SockJS browser support  
- Clean MVC backend structure  
- Java 17 compatible  

---

##  Tech Stack

Backend:
- Java 17  
- Spring Boot  
- Spring Web  
- Spring WebSocket  
- STOMP Messaging  

Frontend:
- HTML  
- Bootstrap  
- SockJS  
- STOMP.js  

---


---

##  How the Application Works

1. User opens the chat page in browser  
2. Browser connects to WebSocket endpoint  
3. Message sent to application destination  
4. Spring processes message  
5. Message broadcast to all connected users  
6. Users receive messages instantly  

---

##  Running the Project

### Prerequisites

- Java 17  
- Maven  
- IntelliJ / Eclipse  


---

##  Messaging Endpoints

- WebSocket endpoint → `/chat`  
- Send message → `/app/sendMessage`  
- Broadcast topic → `/topic/messages`  
- Chat page → `/chat`  

---


##  Future Improvements

- Authentication system  
- Database message storage  
- Private messaging  
- Chat rooms  
- AI chatbot integration  
- Notifications  
- Deployment  

---

##  Author

Souhardya Banerjee  

