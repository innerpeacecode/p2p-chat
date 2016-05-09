A simple mutli-threaded chat server written in Haskell 

Run server:

```
$ link <port>
```

Command to the server over TCP:

```
$ telnet <host> <port>
```


Commands sent to the server:

- `LOGIN <username>` Login with the username
- `QUIT` Quit the server
- `MSG <username> <message>` Send a private message to a user
- `JOIN <channel>` Join a channel
- `LEAVE <channel>` Leave a channel



