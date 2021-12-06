# Concurrent-TCP-Server
This creates a concurrent TCP server that accepts incoming messages from multiple TCP clients and responds with the number of clients currently connected to it.

To run, download the files.
In the concurrentserver directory (the server needs to be started first), run in the terminal
```shell
go run concurrent_tcp_server.go <PORT>
```

In the tcpclient dir, open a new terminal and run
```shell
go run tcp_client.go 127.0.0.1:<PORT>
```
A >> prompt will appear to enter text. Type sometext and the server will respond. <br>
You can also make new TCP connections using netcat.
