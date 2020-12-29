# AWS: S3 and Lambda

## Review, Research, and Discussion

  1. What’s the difference between a FIFO and a standard queue? Fifo queues are essentially the same, but supports ordering and ensures exactly once procesing to make sure there are no duplicated tasks running.
  2. How can the server be assured a message was properly received? Add a response/confirmation into the program so the server will receive an "all clear" signal so it knows the message was delivered and read.
  3. What classic design pattern is best represented by event driven programming? A messaging service?
  4. How do you test an event driven system? Unit tests, service tests, and end to end tests source
  5. Vocabulary:
    - Server Instances: A single virtual machine hosting server software.
    - Containers: A standard unit of software that packages up code and all of it's dependencies 
    - Cloud Services: services available off site via cloud computing software, that delivers services on demand to users over the internet
    - Cloud Architecture: defines the components of cloud services
    - AWS: Amazon Web Services: provides technology services from a remote area, decreasing the amount of overhead required for expenses.
    - EC2/Beanstalk vs Heroku: biggest difference between the two is in regards to how much we need to continually update our infrastructure and the purpose of the applications being built. EC2 requires a full time DevOps person continually managing the platform, while Heroku is a "platform as a service" and mostly handles the details if you know how to ask for them. 
    
## Preview
  1. Which 3 things had you heard about previously and now have better clarity on? What AWS does, how to access things on it, how to deploy a basic app on it.
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? How to use AWS more dynamically, why there's so much difference between each of us (classmates) in getting AWS to work on our machines, and (always) testing.
  3. What are you most excited about trying to implement or see how it works? Uploading real apps on AWS, how they tie together with an actual web address.
  
## AWS S3
  - Amazon Simple Storage Service: Object storage service that offers scalable storage space, as much or as little as is needed.
  
## AWS Lambda Basics/AWS Lambda Functions
  - Serverless computing system: doesn't mean there are actually no servers, it just means the servers are already provided for you to run your code on.
## CDN
  - Content Delivery Network: Geographically distributed group of servers that help provide fast delivery of services. Speed is improved by having servers closer to the user, which is helpful when considering the sercurity of servers.

    
    
    
    
    
    
