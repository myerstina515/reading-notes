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

## Additional Resources


