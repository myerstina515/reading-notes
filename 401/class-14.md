# Event Driven Archetecture

## Review, Research, and Discussion
  1. What’s the difference between a FIFO and a standard queue? They are very similar in function, but in a FIFO queue, ordering is supported and helps to ensure only one copy is ever sent. It's called "exactly once processing" [source](https://cloudaffaire.com/sqs-standard-vs-fifo-queue/)
  2. How can the server be assured a message was properly received? The client would send a return message stating 'received' once the message was received and viewed.
  3. What classic design pattern is best represented by event driven programming? Event driven archetecture is the best answer I was able to find [here](https://en.wikipedia.org/wiki/Event-driven_architecture)
  4. How do you test an event driven system? Currently, we test by spying on the console, looking to see that console log's have been called for particular events
  5. Vocabulary
    - FIFO Queue: FIFO (First in, First out) refers to a queue where the first node entered becomes the front, and when one is removed from the queue, it removes the front, so in literal terms, the first one in is also the first one out.
    - Pub/Sub: publish/subscribe pattern: messaging pattern where applications can subscribe to asynchronous events.
    
## Preview
  1. Which 3 things had you heard about previously and now have better clarity on? FIFO, queues, stacks
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? TESTING. Also I'm looking for more clarity on the messaging portion of our lab we did today, and to learn about AWS (which it looks like we learn about tomorrow!)
  3. What are you most excited about trying to implement or see how it works? Still looking for clarity on today's lab.
  
## SNS vs SQS
[video](https://www.youtube.com/watch?v=mXk0MNjlO7A)
  1. SNS: Simple Notification Service: publisher/subscriber system; subscribers get notified of messages posted: Fan out approach:
  - Purchase being approved by the credit card authorization service-- message gets sent out and is available globally.
  2. SQS: Simple Queue Service: could be a subscriber to an SNS: Pulls queue to discover new events: Messages processed by single consumer:
  3. Do other systems care about an event? If yes, use SNS because you want to publish the event, if no, use SQS (do YOU care if something happens elsewhere)
  
## Azure Event Hubs
  1. [video](https://www.youtube.com/watch?v=DDDjFQSQyF4)
  2. Discusses different features for the Azure Messaging via event hubs
    
    
    
    
    
    
    
    
    
    
    
    
    
    
