# Message Queues

## Review, Research, and Discussion

  1. What does it mean that web sockets are bidirectional? Why is this useful? Means either the client or the server can send a message to the other. It's helpful because when one message is sent, the other one can respond, so it's not just unilateral.
  2. Does socket.io use HTTP? Why? It does, yes, it integrates with HTTP
  3. What happens when a client emits an event? When the event is invoked, the client emits, or sends, the event to the server via websocket.
  4. What happens when a server emits an event? A callback function is used to invoke the event on the server side.
  5. What happens if a client “misses” an event? A missed event triggers nothing. 
  6. How can we mitigate this? To prevent this, we need to make sure all of the listener functions are in the correct position, turned on, and functioning properly.
  7. Vocabulary
    - Socket: Serves as an endpoint for sending or recieving data through the internet.
    - Web Socket: Web Socket is a protocol for transmitting data from one computer to another, where data is sent in chunks as able.
    - Socket.io: A library that helps client and server side applications to respond to events.
    - Client: The user side of a web application
    - Server: The back end processing side of a web application that runs the application on a host.
    - OSI Model: Open Systems Interconnection Model: characterizes functions into a set of rules and requirements to support compatability between different products and operating systems [source](https://www.forcepoint.com/cyber-edu/osi-model#:~:text=The%20OSI%20Model%20(Open%20Systems,between%20different%20products%20and%20software.)
    - TCP Model: Transmission Control Protocol Model: A much more specific and detailed version of the OSI model
    - TCP: Transmission Control Protocol
    - UDP: User datagram Protocol: Faster protocol that allows data to be transferred without confirmation from the reieving party.
    - Packets: Formatted unit of data that is abel to be sent via TCP model from one party to another.
    
## Preview
  1. Which 3 things had you heard about previously and now have better clarity on? socket.io, client/server functions, events
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? testing (always testing), additional explaination of socket.io, different models of data transmission.
  3. What are you most excited about trying to implement or see how it works? Always testing.
  

  
  
  
  
  
  
  
  
  
