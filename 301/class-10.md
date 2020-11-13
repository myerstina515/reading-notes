# Reading Notes Class 10

## Call Stack defined

  1. Call stack: mechanism for an interpreter to keep track of it's place inside functions (which one is being run, and what functions are called from inside it). It has a stack of functions, and once a function is called, it is at the top of the stack, but when it finishes running, it is removed from the stack. If it takes up more space than is assigned to it, it is called "stack overflow" and throws an error.
  
## The JavaScript call stack: What it is and Why it's necessary

  1. The call stack is a single line of query, where only one function can be called at a time, and goes from "last in, first out" processing. When we run code, a stack of functions is printed and will show exactly where the error occured, and will not run though any additional functions at that point. The stack appears to use similar terminology as arrays (push, pop). A stack overflow occurs when one of the functions calls itself without an exit point. 
  
## Javascript error messages and debugging

  1. Most of our time as developers is spent debugging (or, as the article jokes, solving an extra feature). There are many types of errors, such as: reference errors (when you try to use a variable that has not been declared), syntax errors (some as simple as a trailing comma), range errors (trying to manipulate the length of something that is beyond it's allowable length), type errors (when the type of character does not match what it should be). Debugging: console.log's, breakpoints, and debug in VSCode. Call stack: As it's mentioned above. One tip they suggest is making sure your functions all have names (no anonymous functions), so it's easier to find the errors. Catch: it's important to catch your errors in code, so the machine isn't stuck in a constant reload cycle. Tools to avoid errors: eslint (which we already use), and quokka are good tools to help decrease errors as you code.
