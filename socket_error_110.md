_**Warning:** socket\_connect() [function.socket-connect]: unable to connect [110](110.md): Connection timed out_


### Introduction ###

Apparently, your server does not support sockets, or any server setting is blocking it. But those sockets are neccessary for ezStats to contact your gameserver.


### Whats next? ###

Please contact the support of your webserver. Please write them the message below, and hopefully they change the settings of your server then. Replace the numbers in the message with your IP and Queryport

### Message ###

I have executed the following PHP-Code on my server, and on a server of another provider:
```
    socket_connect(
        socket_create(AF_INET, SOCK_STREAM, SOL_TCP),
        "123.456.789.012",
        12345
    );
```

While on the foreign server, the connection is established, on my server, this error appears:
```
    Warning: socket_connect() [function.socket-connect]: unable to connect [110]: Connection timed out in ...
```

Please change the settings of my server, so I can use sockets.