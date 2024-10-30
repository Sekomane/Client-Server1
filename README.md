# Java Client-Server Communication Program
This repository contains a simple Java client-server program designed to facilitate real-time communication over sockets. The client and server exchange messages using BufferedReader and BufferedWriter for efficient input and output handling.

#Features

-Client-Server Communication: Enables text-based message exchange between client and server over a TCP connection.
-Multi-Message Exchange: Allows continuous message exchange until either party sends "BYE" to terminate the connection.
-Error Handling: Includes basic exception handling to manage IO errors and ensure proper resource cleanup.
-Socket Management: Utilizes ServerSocket on the server side and Socket on the client side to manage network connections.

#Usage
1.Start the server program, which listens for connections on port 1234.
2.Run the client program to connect to the server.
3.Type messages on the client console, and observe responses from the server.

#Output Below
![Screenshot (465)](https://github.com/user-attachments/assets/15799ad3-b134-46c4-970a-272569462bcf)
