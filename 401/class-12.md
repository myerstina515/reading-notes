# Socket.io

## Review, Research, and Discussion

  1. What is the benefit of transforming data into packets? A packet takes chunks of data and sends them separately into the internet, with each packet taking the path that is available to it at the time it can go. [source](https://whatismyipaddress.com/data-packets)
  2. UDP is often refereed to as a connectionless protocol. Why is this? UDP (or user datagram protocol) is called a connectionless protocol because it essentially takes data and sends it directly to another computer, without establishing a connection first, and without checking to see if it arrived. [source](https://www.cloudflare.com/learning/ddos/glossary/user-datagram-protocol-udp/)
  3. Can a socket server application have multiple socket connections? Yes, by using socket.io
  4. Can a socket connection application be connected to multiple socket servers? Yes, as long as they are set on separate ports.
  5. Can an application be both a socket server and a socket connection? I believe so, yes, but I can't fully put it into words.
  6. Vocabulary:
    - Observer Pattern: Where an object (subject) has a list of dependants (observers) where the observers are updated automatically of any changes to the subject.
    - Listener: Term used with events, the listener listens for an event and routes it to it's assocaited handler function.
    - Event Handler: responds to an event after the listener "hears" it.
    - Event Driven Programming: Where the program is determined strictly by reacting to events.
    - Event Loop: The event loop manages the call stack and callback queue, and refers to the holding pattern of functions in javascript, where one function can be called at a time, and if not specified as async can be completed out of the order as intended.
    - Event Queue: Where events are held until they can be processed.
    - Call Stack: What a program uses to keep track of method calls. The calls wait in "line" until it's their turn to be handled.
    - Emit/Raise/Trigger: methods for triggering an event
    - Subscribe: the method used to create observers on a subject
    - database: where data is stored and requested from -- makes data retrieval happen locally instead of use of a public API
  
## Preview
  1. Which 3 things had you heard about previously and now have better clarity on? testing, object creation, and event loops
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? testing (always), functionality of call stacks and event queues beyond the code challenges.
  3. What are you most excited about trying to implement or see how it works? Still excited for more clarity on TDD.

## Additional Resources

### Web Sockets
1. designed to work over certain HTTP ports (443 and 80), to enable interaction between browser and server, specifically by allowing messages to be sent back and forth easier. It begins with a standard WRRC, then communication switches to a binary protocol instead of HTTP. The connection also makes use of base-64 encryption as well as hashing, and the data can be sent in small chunks as it is able, wihtout waiting for confirmation or response.
### Socket.io tutorial
1. Socket.io is a JS library: client side and sever side included in the package. Some examples of web apps that use socket.io for auto refreshing are What'sApp, gamnig platforms like CoD, facebook messenger, google docs, etc. Much easier to implement than language stacks like LAMP. Primarily uses Express.js as a base library.
2. started with *npm install --save express socket.io*
3. *var http = require('http').Server(app);
*var io = require('socket.io')(http);
*//Whenever someone connects this gets executed
*io.on('connection', function(socket) {
*console.log('A user connected');
*//Whenever someone disconnects this piece of code executed
*socket.on('disconnect', function () {
 *  console.log('A user disconnected');
*});[source](https://www.tutorialspoint.com/socket.io/socket.io_hello_world.htm)
4. The remainder of the tutorial walks the user through the remainder of set up for use of socket.io (continue to follow along [here](https://www.tutorialspoint.com/socket.io/socket.io_hello_world.htm))


### Web Socket vs Socket.io
1. Web socket works in real time and stands over an HTTP connection that provides full "duplex" communicatino. It lives up to the standards, removes overhead, and makes communication efficient and smooth. Doesn't have fallback options. Websocket is a technology, while socket.io is a library that works on websocket.
2. Socket.io upgrades automatically to web socket if needed, helps for app based communication, helps in broadcasting to multiple sockets at one time, and works on all platforms. Socket.io handles all the varying inconsistencies between browsers and has extra features such as automatic reconnect.

### OSI Model explained:
(https://www.youtube.com/watch?v=vv4y_uOneC0)
1. Helps explain how data is transferred from one computer to another. In order to improve computer communication between computers with different running software, made in 7 layers: applicaton layer, presentation layer, session layer, transport layer, network layer, data link layer, and physical layer.
2. Application layer: Provides services for nework applications with help of with help of protocols. 
- Presentation; receives data from layer 1, completes data compression to store file in smallest size possible. 
- Session: helps in setting up and managing connections, and terminates at the end, uses API's, and tracks authorization and authentication. 
- Transport: controls reliability of communication through segmentation. Data is divided into smaller units called segments.  
- Network: Sends packets, logical addressing, IP address assignments, routing. 
- Data Link: recieves data packet, logical addressing and physical addressing takes places via IP address. Accesses media, error detection. 
- Physical Layer: Data has been segmented, and placed into package, and framed by data link. Transmits over local media, uses binary signal. Signal depends on the media type.

### TCP - Three way handshake
(https://www.youtube.com/watch?v=xMtP5ZB3wSk)
1. Transmission control protocol. Connection oriented protocol. Data can be delivered successfully and accurately. Uses 3 way handshake to establish connection before transmission. TCP connection has to be established in 3 steps: Step 1: Client sends SYN segment to the server, asking for synchronization. Step 2: SErver replies with SYN-ACK, to acknowledge the request for the connection. Step 3: Client replies with ACK ( indicating "yes" ).













