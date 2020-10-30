# Reading Notes Class 10

## JavaScript

   - **Chapter 10 "Error Handling and Debugging"
     1. When trying to find errors and debugg, you have to follow the order of the execution which sometimes means starting in a 1, 2, 3 process, but sometimes it can go in order and then jump completely out of order or back to the beginning. The JS interpreter processes one line at a time, but sometimes needs to grab data from another function, so it will leave that one where it is until it finds the correct information (called "stacking").
     2. When there is an error, the browser will generally walk you through what the problem is, it will tell you the name of the error, followed by what line of what code the error occurred on.
     3. Each different browser had a different way of looking at errors, but I will be discussing the Chrome method as that is the one that we do the most work in for class. Chrome utilizes breakpoints, which point to a particular spot in time in your code. It is possible to pause the cycling of code and to progress through one step at a time, which takes you through the order of execution.
     4. It is possible to intentionally throw errors in your code, if there is an expected error, for example a user entering a string where a number is expected. It prevents the code from running longer and throwing a different code that could cause other issues. Just remember, some errors are browser specific, so changing browser may actually help fix the error.
