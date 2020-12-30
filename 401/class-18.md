# AWS: API, Dynamo and Lambda

## Review, Research, and Discussion
  1. What’s the difference between a FIFO and a standard queue?Fifo queues are essentially the same, but supports ordering and ensures exactly once procesing to make sure there are no duplicated tasks running.
  2. How can the server be assured a message was properly received?Add a response/confirmation into the program so the server will receive an "all clear" signal so it knows the message was delivered and read.
  3. What classic design pattern is best represented by event driven programming?A messaging service?
  4. How do you test an event driven system? Unit tests, service tests, and end to end tests source
  5. Vocabulary:
    **-1.** Serverless Functions: Serverless functions are single purpose functions that are hosted on a managed hosting tool, written for a single purpose, like on Lambda
    **-2.** Cloud Storage: Off site remote storage space, hosted by a cloud infrastructure platform, where you can take up exactly how much computing space you require, no more and no less.
    **-3.** CDN: Content Delivery Network: geographic distribution of servers so it takes less time for the information to transfer from the cloud storage to the user.
    
## Preview
  1. Which 3 things had you heard about previously and now have better clarity on? After class today I had better clarity on the CAPS assignment and use of constructors, uploading on AWS is more clear, and testing feels a little bit better.
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Testing (always testing), how to make CLI like me better, and why we needed to upload node_modules when I thought node_modules were built in for AWS.
  3. What are you most excited about trying to implement or see how it works? One day AWS will feel comfortable...
  
## AWS API Gateway
  1. Hosts API's and helps with the managing and interacting of the same. Works with RESTful API's and websocket API's, and integrates with other AWS resources to allow for fully managed authentication and authorization layers.
  2. Works well with the serverless model so the host can use as much or as little space as needed to fully utilize their application.
  3. Uses Lambda to make events easy to access. 
  4. Benefits to using Gateway: SAving time by having AWS manage the performance of the website, able to use mulitple microservers for one API, able to map a websocket API, and able to map an HTTP request with the gateway, eliminating the need for a dedicated API server.
  5. Drawbacks: Can get expensive with increased times (in milliseconds) to process data, can't fine-tune the gateway to fit your needs, as it's a managed service.
  
## Dynamo DB
  1. Key-value and document database that can handle 10 trillion requests per day and up to 20 million requests per second. Used by many current day companies such as Lyft and Redfin.
  2. Commonly used for ad companies as well as for gaming uses, retail, banking and financing, and of course, software.
  3. Helps to improve security and decrease instance of "bots" on some commonly used sites or commonly played games.
  

## Dynamoose
  1. Modelling tool for Dynamo DB, similar in use as Mongoose is to Mongo DB. 
  2. Takes us through an installation process, but I'll bookmark and add once I know what we're doing.








