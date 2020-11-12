# Reading Notes Class 9

## Concepts of Functional Programming in Javascript
  1. Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia
  2. Pure Functions: always return exactly the same result if given the same set of parameters, and doesn't have any side effects in the rest of the program. Impure functions use global variables and compute things. If our function reads external files, it is not pure, random mumber generators, and incrementing values are all examples of impure functions. Pure functions are much easier to test.
  3. Immutablity: it's state cannot be changed after it is created. For loops are one example of values that mutate, as it changes every time it iterates through the loop. When we reduce a function, it keeps variables immutable.
  4. Referential Transparency: If a function always returns the same value, given the same input, it has referential transparency. Basically, pure functions + immutability = referential transparency.
  5. Fuctions at first class entities: These functions are treated as values and are also used as data. Higher order functions: take more functions as arguments or produce another functions. Filter: function that takes in a string of values and returns an array of the values separated by some criteria. Map: transforms an array into a different array, by transforming the values at certain indexes. Reduce: receive a function and a collection, and return a value by combining the items (example: looking in an online shopping cart after placing 4 items in the cart. The items and the dollar amounts combine to give you a total). 



## Refactoring JavaScript for Performance and Readability
  1. Scenario 1: User enters short URL that forwards them through long URL to website. The way to refactor is to change the structure of the data. Using a hash function will give a key to the location, which will decrease the amount of "buckets" the function needs to look for and the website will run faster.
  2. Scenario 2: Social media website where users names are randomly generated from a list of "friendly" words. The one function does only create the user, but as the site grows it will be doing many more things and take much longer. So, they break up the function so it's smaller chunks of logic.
  3. Strategies: 
    a. Return early from functions
    b. Cache variables so functions are more readable
    c. Check for web API's before implementing your own functionality.


