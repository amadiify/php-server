# Simple PHP Server
This is a simple PHP Server. You are required to have PHP ^7.2 running on your machine.

## How to start a server on a static port
This would start a development server on port 9090. 
```bash
    php server.php 9090
```


## How to start a server on a dynamic port
This would start a development server on a random avaliable port. 
```bash
    php server.php
```

## How to start a server on a static port without opening a new tab
This would start a development server on a static port without opening a new browser tab. 
```bash
    php server.php 8081 -notab
```

Please note, by default the server would check for ```index.php``` to include as the base file.