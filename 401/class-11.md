# Event Driven Applications

## Review, Research, and Discussion

  1. Why is access control important? Access control helps to define what access is needed by each person in an organization. It helps to keep private or classified things private or classified to only those that have reason to know about them. 
  2. Describe an application that would need access control. Medical charting software needs access control to ensure HIPAA regulations are adhered to as well as making sure people can't adjust medical records and documentation without being a licensed professional.
  3. What is a role used for? When you define different roles by what they can and can't do, you assign a role to someone in the organization that automatically decides what they have access to based on their "role". It helps to control what each employee has access to, which helps with productivity.
  4. Why is role based access control more scalable than discretionary or mandatory access control? Mulitple roles can be assigned with role based access control, which ensures if someone has needs to specific things, they can get it automatically. Discretionary access control, if I remember correctly, means that someone can have access to find out one thing, but it becomes much more difficult to regulate and be sure that people don't have access that isn't required.
  
  5. Vocabulary:
    - Authorization: temporary code that user can exchange for a token that will grant them access to a website for a certain period of time.
    - Role Based Access Control: Uses roles to determine what information or capabilities a user has (i.e.- admin, user, editor)
    - Capabilities: What a user is allowed to do with regards to access control. Each user has specific things they are approved to do, and nothing more to ensure sensitive operations are only completed by authorized people.
    
## Preview

  1. Which 3 things had you heard about previously and now have better clarity on? testing, access control, authorization
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? testing (always wanting to learn more about it), event driven programming, TDD
  3. What are you most excited about trying to implement or see how it works? Still excited/wanting to learn more about testing. I say that most days and am learning more, but still interested to build tests line by line like we did on Friday.
  
## Event Driven Programming
  1. Makes use of concepts like event listeners and a main loop listening to events and routing it to the appropriate handler function. We have been going over event driven programming since we started, which is interesting since the term hasn't been used yet, but makes sense. We use EventEmitter to process this.
  2. EventEmitter has an *emit* method that triggers the event. When the event is complete, it's important to remove the event listener so objects don't continue to pile up and to reset the listener so it can listen for the event again (i.e. chat room when someone enters and everyone is notified)
  3. It's common to use object oriented programming alongside event driven programming, so each event is being listened for on a particular object, and the object is being handled within that event.
  
## Node docs (events)
  1. Bookmarked and ready to reference
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  



