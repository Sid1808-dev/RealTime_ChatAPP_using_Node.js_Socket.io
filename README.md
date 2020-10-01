# RealTime_ChatAPP_using_Node.js_Socket.io
This is a real time chat application developed with the help of Node.js and Socket.io. It allows a two side connection between the server as well as the user, which helps in real time transfer of information. This indeed is much faster than usual protocols used in server side communication.

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/60344472/87045307-5e467900-c215-11ea-8f42-86498dc5fb81.gif)

# Here is an info about how Socket.io works and how its better than normal server side communication
Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server. It consists of:

a Node.js server: Source | API
a Javascript client library for the browser (which can be also run from Node.js): Source | API

How does that work?
The client will try to establish a WebSocket connection if possible, and will fall back on HTTP long polling if not.

WebSocket is a communication protocol which provides a full-duplex and low-latency channel between the server and the browser. More information can be found here.

So, in the best-case scenario, provided that:

the browser supports WebSocket (97% of all browsers in 2020)
there is no element (proxy, firewall, …) preventing WebSocket connections between the client and the server

For more info on socket io see the documentation here: https://socket.io/
