# Java Chat Application

This repository contains a simple Java-based chat application designed to demonstrate the basics of network programming, client-server relationships, and real-time messaging. The application enables users to connect to a central server and exchange messages with other connected users in real-time.

## Features

- **User Authentication**: Simple login mechanism to identify users.
- **Private and Group Chat**: Users can send messages privately to another user or broadcast to a group.
- **Real-Time Messaging**: Messages are delivered and displayed in real-time.
- **Multi-Threaded Server**: Handles multiple client connections simultaneously.
- **GUI Interface**: A user-friendly graphical interface for interacting with the application.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher.
- Basic knowledge of Java and network programming.

### Installation

1. Clone the repository to your local machine:
git clone https://github.com/yourusername/java-chat-application.git
2. Navigate to the cloned directory:
cd java-chat-application
3. Compile the source code:
javac Server.java Client.java
4. Start the server:
java Server
5. Open another terminal window and start the client application:
java Client
6. Follow the on-screen instructions to connect and chat.

## Usage

After starting the client application, enter your username to connect to the chat server. Once connected, you can send messages to all connected users or specify a username to send a private message.

