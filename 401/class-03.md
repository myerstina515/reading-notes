# Reading Notes Class 3

## Review, Research, and Discussion

  1. Name 3 real world use cases where you’d want to change the request with custom middleware: Changing the path to retrieve API information from a database rather than long timely API calls, hiding routes, validate names.
  2. True or false: The route handler is middleware? False-ish. The route handler can contain middleware, but is not middleware in and of itself. 
  3. In what ways can a middleware function end the process and send data to the browser? It can end the function and send data to the browser with .next(with or without a string in the parens), .then, and .catch as some examples.
  4. At what point in the request lifecycle can you “inject” middleware? Anytime, as long as the request hasn't reached the server. As we talk about in class, it's like a stop sign that can appear anywhere along the "tracks" of the request.
  5. What can cause express to error with “Request headers sent twice, cannot start a second response”: having a next() in the wrong place, or in a function where it doesn't belong, or when a response is requested more than one time in a function. It cannot respond more than once. 


### Document the following Vocabulary Terms

  - Middleware: It's software that is able to be added onto a server to allow the server to do more things than it can do on it's own.
  - Request Object: It is the client asking the server to send it some information.
  - Response Object: It is the data that gets sent back to the client from the server.
  - Application Middleware: This is the actual middleware that is present during the request, acting as stop signs along the train track.
  - Routing Middleware: It defines the different routes.
  - Test Driven Development: A development style that revolves around frequent testing of your code base and application to ensure it's in working order and could be deployed at any time.
  - Behavioral Testing: also known as "black box testing", a style of development where the internal structure and design of the item is not known to the tester. [*source*](https://softwaretestingfundamentals.com/black-box-testing/)


## Preview

  1. Which 3 things had you heard about previously and now have better clarity on? After having to think about the review questions, I understand the ending of the process and sending data to the browser, as well as the request headers sent twice. I ran into that error a couple times during the lab today (Tuesday).
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? I'm hoping for more clarity on the different types of middleware (middleware, application, and routing), as well as behavioral testing and additional testing techniques in general.
  3. What are you most excited about trying to implement or see how it works? I want to spend more time working on tests and techniques for them, as well as UML.






