# AWS: S3 and Lambda

## Review, Research, and Discussion

  1. What’s the difference between a FIFO and a standard queue? Fifo queues are essentially the same, but supports ordering and ensures exactly once procesing to make sure there are no duplicated tasks running.
  2. How can the server be assured a message was properly received? Add a response/confirmation into the program so the server will receive an "all clear" signal so it knows the message was delivered and read.
  3. What classic design pattern is best represented by event driven programming? A messaging service?
  4. How do you test an event driven system? Unit tests, service tests, and end to end tests source
  5. Vocabulary:
    - Server Instances
    - Containers
    - Cloud Services
    - Cloud Architecture
    - AWS
    - EC2/Beanstalk vs Heroku
