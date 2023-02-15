# golangChattApp
WebSocketChattApp with Golang

In this chapter we will learn how to implement web sockets in Go, to create a chat application. The web socket server is built using the Gorilla Web Socket library, and on the front end we use JavaScript's native API, namely WebSocket to communicate with the socket server.

Obviously web socket capabilities can be achieved by simply using the default packages provided by Go. But in this chapter learning is done using a 3rd party library.

As usual, the learning process is carried out while practicing. We make a minimalist chat application, with as little code as possible so it's easy to understand, development is done from scratch.

Later during testing there will be many users connected to the server socket, in one room. Every message written by one user can be read by all other users.
