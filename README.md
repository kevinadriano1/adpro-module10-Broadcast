## understanding How It Works

![alt text](img/ss1.png)

In this experiment, we explored a broadcast chat application using asynchronous programming and WebSockets in Rust. One server process was started to listen for incoming connections, and three clients were launched from different terminals. When a client sends a message "hello1", "hello2", "hello3", the server receives and broadcasts it to all connected clients. every client prints out all the messages sent by any other client, demonstrating real-time message delivery. This behavior is enabled by asynchronous tasks that allow the server to handle multiple connections concurrently without blocking. It shows how async programming is well-suited for real-time applications like chat, where responsiveness and concurrency are essential.