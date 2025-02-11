# Chat Application using WebSockets in Spring Boot

## Overview

This is a real-time chat application built using WebSockets in Spring Boot. The application supports a single chat room where multiple users can communicate in real time.

## Features

- Real-time messaging using WebSockets
- Single chat room for all users
- Efficient handling of concurrent WebSocket connections
  ![image](https://github.com/user-attachments/assets/40734791-1c26-4f9f-bf7a-d5b1acb6549b)
![image](https://github.com/user-attachments/assets/6eaf3162-cd58-4990-8264-7bff4b915219)


## Technologies Used

- Java (Spring Boot)
- WebSockets (STOMP Protocol)
- Maven (Build Tool)

## Installation

### Prerequisites

Ensure you have the following installed:

- Java 17+
- Maven

### Steps to Run the Application

1. Clone the repository:
   ```sh
   git clone https://github.com/grithwikreddy/ChatApplication-using-Websockets-in-Spring-Boot.git
   cd chat-application
   ```
2. Install dependencies:
   ```sh
   mvn clean install
   ```
3. Run the application:
   ```sh
   mvn spring-boot:run
   ```
4. Test WebSocket connection using WebSocket King Client.

## WebSocket Endpoints

- **Connect**: `localhost:8080/chat`
- **Subscribe**: `/topic/messages`
- **Send Message**: `/app/chat`


