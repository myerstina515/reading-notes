# Reading Notes Class 6

## Review, Research, and Discussion

  1. Explain what a “Singleton” is (in Computer Science terms)
    - An alternative to global variables and static classes, it refers to a pattern that restricts instantiation to a single instance. It's common to use them with a "factory" which churns out lots of objects that are the same as each other, it simplifies the code. 
    - They don't take up space like global variables do, but they can have parameters passed to them and they are able to have their instances swapped out for testing. [reference](https://medium.com/better-programming/what-is-a-singleton-2dc38ca08e92)
  2. Explain how the Singleton pattern can be used with Node modules, specifically with classes.
    - A singleton pattern in a Node module will basically make a single object within the class, and act as a factory, creating that one single object when information is passed. 
  3. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
    - In our code, original middleware is called within a function of a route, can be modularized by taking it out of the flow and placing the function in its own folder. It is then called in the function where it's used. So if I were creating a middleware system, I would act similarly. I would create tests first, then design the middleware around the tests, in order to be sure that when it's used by other developers, it acts as expected. 
    
  4. Vocabulary:
    - Router Middleware: acts as the stop sign along the train track metaphor. Sends additional information along with a request, adjusting the information that is being transported to the next() step.
    - Dynamic Module Loading: loading modules when necessary, or on demand, rather than loading everything at one time all at once, regardless of needing that amount of data. 
    - Singleton Pattern: restricts intantiation to a single instance (as above).
    - CRUD -> REST Method Matches: 1. "Create" = "Post" 2. "Read" = "Get" 3. "Update" = "Put" 4. "Delete" = "Delete"
    - Mock Testing: Creating a fake version of a test so the test will pass easier
    
## Preivew:

  1. Which 3 things had you heard about previously and now have better clarity on?
    - I've heard the term singleton before, but had no idea what they were. Interested to learn more about them tomorrow.
    - Friday and over the weekend, I learned lots more about Big O, and feel like I have a working understanding of the term, though I'm sure there's plenty more to learn about it. 
    - I have much better clarity on the linked lists after the code challenge over the weekend. I read about them previously (last reading assignment), but seeing how it translates to the code makes much more sense now. I'm sure that will change with the code challenge tomorrow, but i feel ok about it right now.
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - I'm hoping to have more clarity on the Mongo and Mongoose actions, I didn't have time to ask the TA's on Saturday for more explaination, so am looking forward to having time this week sometime to understand futher.
    - Writing tests
    - Linked lists (dive deeper into them)
  3. What are you most excited about trying to implement or see how it works? I'm really looking forward to the day that test writing seems easier... It's still rough.
  
## Securing passwords:
  1. Most strong passwords are stored via cryptographic hash algorithms, which are considered pretty safe password storage. some vocabulary:
    - Brute Force attack: Hash algorithms don't change, so a brute force attack via computer can take as little as an hour with a hash algorithm,up to 16 characters.
    - Hash Collision attack: Since they have indefinite length, eventually there will be two combinations that producte the same hash algorithm, which produces a hash collision attack.
    - Key Stretching: to overcome the issues with hash algorithms, there are other slower methods for 
















