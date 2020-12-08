## Reading Notes Class 1

### Describe (in plain English) what Array.map() does
* Array.map is similar to a for loop, it takes an array and creates a new array that does a particular thing to each individual element of the first array until it has gone through all of the elements.

### Describe (in plain English) what Array.reduce() does
* Array.reduce is similar to array.map, in that it takes an array and does something to each element of it. It goes through the array and executes a function on each item of the array, takes into account what the first value is, then uses an accumulator, which accumulates all of the values into one single value.

### Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
    1. With normal Promise .then() syntax:
    
    * superagent.get(url)
    .then( data => {
      console.log(data.body.results);
    })
    .catch( err => console.error('ERROR:', err))
    
    
    2. Again with async / await syntax
    
    try { superagent(url)
      let data = await data.body.results;
    } catch(err) {
      console.log(err)
    }


### Explain promises as though you were mentoring a Code 301 level student
  1. A promise is an async object that may or may not return a value later on. It can have three states, resolved, rejected, or pending. Typically, if it's pending and you receive an error, it hasn't had time to resolve or reject, which is when a ".then()" can be called. If resolved, it will return the value, if it is rejected, it will return an error.


### Are all callback functions considered to be Asynchronous? Why or Why Not?

No, not all functions are asynchronous. An alert would be an example of a function that is not asynchronous. The next thing does not happen until that particular function is resolved. Asynchronous functions are those that continue working while something else is happening. Sometimes that is a problem, as the thing the website is waiting on (fetching data for example) isn't fast enough, and in another place of code you may have something that relies on the data that is taking a long time to fetch. 
