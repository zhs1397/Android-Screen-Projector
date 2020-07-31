# AndroidScreen Projector
A simple demo for remote projection and control based on android.

## Features
Screen projections encoding based on h264 stream, while use ffmpeg for decoding on Client
supports touch down, touch up as well as scroll 

### Running the server
To run the demo, follows these steps:
```
1. run runServer.bat to start the server on Windows
2. run the client project on IntelliJ to start the client on Windows
```

or you can build the file on your own:
```
1. use gradle on AndroidStudio to build file for server
2. use maven on IntelliJ to build file for client and use 'java -jar @dest' to start the client
```

