## Reading Notes Class 02

### Review, Research, Discussion:

  1. What’s the difference between PUT and PATCH? Put replaces or updates the entire set of data, while patch replaces only specific pieces of data.
  2. Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
    - https://www.mockapi.io/
    - https://stoplight.io/mock-api-guide/basics/
    - https://designer.mocky.io/
    
  3. Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
    - Both tools allow for mock API development. APIDoc.js does templating, while swagger returns a .json or .yml file.
  4. Compare and contrast SOAP and ReST
    - SOAP: Simple Object Access Protocol: Much more rigid and secure protocol (not style), that keeps information more secure than a typical ReST-ful app. Makes for a standardization of messaging.
    - ReST: Representational State Transfer: Supported by most browsers, flexible, and supports JSON responses (could use SOAP protocol). ReST is a style of full stack app development.
  
  5. Vocabulary Terms:
    - Web Server: "serves" information (or a website) to the front end client side. It handles all of the processing and storing of data, and is essentially the host of a webiste.
    - Express: Express is a javascript framework that allows developers to create the server side of web applications.
    - Routing: Routing provides pathways to send a user from one area of a website to another based on what the user does on the client side.
    - WRRC: Web Request/Response Cycle: the cycle of back-end web development that begins with the client side request of information to the server, and the response of the server to the client side with the requested information. The front end and server side are one example of this, another is the server side interacting with API's, as well as the server side interacting with a database. 
  
### Preview:

  1. Which 3 things had you heard about previously and now have better clarity on?
    - Mock API's (I had heard about them, but didn't understand how you could have a pretend API)
    - NPM makes better sense now. Before I knew it was what you type into the terminal, but what it actually does is more clear.
    - We have heard of tests before, but it's starting to become clear how they help beyond code challenges.
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - I'm excited to learn about tests and how to write them.
    - Webhooks sound interesting, but the video only touched on it compared to what I'm sure we'll learn about them.
    - Opinionated vs unopinionated frameworks.
  3. What are you most excited about trying to implement or see how it works?
    - I'm honestly really ready to get into the testing portion. We used them so much with code challenges last class and I've been curious the entire time how they work and how to decide what needs to be tested.
  
### Prep materials:
  1. Into to node.js and express
    - Node is a server side environment that helps applications run. It allows utilization of API's and other file system libraries. It's written in regular javascript, so the syntax is easy for beginners to learn, and doesn't require the same shift between languages that many other back-end or front-end languages require. Node is able to be used on nearly all browsers and is supported by many hosting platforms.
    - Express is a Node framework that allows utilization of routes and can interact well with middleware during the request cycle. Both Node and Express are on the opoular end of software, so will likely continue to be updated and utilized, and are unlikely to disappear. 
    - There are opinionated and unopinionated frameworks. Opinionated frameworks have a specific "right ways" to handle tasks, while unopinionated have much fewer restrictions. Express is considered unopinionated, as it is easy to use with many different middle-ware options.
    - Node is single threaded, and uses non-blocking asynchronous API's which means they are in one line, and the next one can't be called until the first one is completed and out of the queue.
  2. NPM:
    - NPM stands for Node Package Manager, and consists of three parts: the website, the command line interface (CLI), and the registry. It helps to incorporate packages, manages applications for updating, and helps with collaboration between developers. 
  3. What is TDD?
    - Test-driven Development: a style of programming where three things are interwoven: coding, testing, and design. 
    - Ideas behind it include refactoring code until it's the simplest possible with tests passing. Individuals can run into issues when they don't test often enough or are writing ineffective tests (tests are too big, too complex, not detailed, etc). Looking through the different levels of testing, we will definitely be in the "beginners" category for a good long while.
  4. CI/CD
    - CI: continuous integration: Helps to ensure everyone's changes will integrate when working on a team where people are working on a large amount of code simultaneously. It helps to catch bugs and decrease merge conflicts. They usually use this in conjunction with automated testing. This helps pave the way for:
    - CD: continuous delivery/continuous deployment: developing software in a way that you could deploy it at any time. Keeps it manageable. Makes it so you can easily deploy new code into action without issue at any time. 
    - Webhooks: GitHub regularly sends out these messages to other systems/servers you give it access to, about activity in your projects.
    - CI/CD tells you when tests pass or don't pass and gives you an idea of what code could be easily added to the code base, without breaking the website.
  
  
  
  
