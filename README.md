# React Socket.io Chat App

This is a chat application built with React and Socket.io. It allows users to join a chat room and send messages to each other in real-time.

## Getting Started

To run this project locally, follow these steps:

### Server

1. Open a terminal and navigate to the server folder:

    ```bash
    cd server
    ```

2. Install the required dependencies for the server:

    ```bash
    npm install express socket.io cors
    ```

3. Start the server:

    ```bash
    npm start
    ```

### Client

1. Open a new terminal and navigate to the client folder:

    ```bash
    cd client
    ```

2. Install the required dependencies for the client:

    ```bash
    npm install
    ```

3. Install the socket.io-client library:

    ```bash
    npm install socket.io-client
    ```

4. Start the React development server:

    ```bash
    npm start
    ```

## Usage

1. Open two different browser windows/tabs and navigate to `localhost:3000` in each one.

2. In one window, enter a username and room ID, then click "Join Room".

3. In the other window, enter a different username but the same room ID, then click "Join Room".

4. You should now be able to send messages between the two clients using the chat application.

Note: Make sure to have the server running before starting the client, as the client needs to connect to the server for the application to work correctly.