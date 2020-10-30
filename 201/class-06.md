# Class 6 reading notes:


## 1. Reading assignment

   - **Problem domain:**
     1. Problem domains are very difficult when you don't have the full picture, which as developers we typically don't have the whole picture. Plus, the problem can look very different depending on what perspective youre looking at it from.
     2. Understanding the problem is the most important and sometimes most overlooked piece of the puzzle. A programmer can spend hours or days on a project, working without fully understanding what the project should look like when it's complete, only to be able to finish in a mere few hours once a full understanding of the expectation is provided.
     3. Though as coders, we want to get to the coding as soon as possible, it's worth taking a little bit of extra time talking to the customer/client to make sure you have a complete understanding of what is being built. What takes an extra couple of hours in time upfront can save days in the long run.
    
## 2. JavaScript and jQuery

   - **Chapter 3: "Object Literals" (p 100-105)**
     1. Objects are here to change our understanding of functions and variables, as they become known as different things when inside an object group. An object is a grouping of variables and functions to create something like what you would see in the world. For example, the "hotel" becomes an object, with the variables becoming properties (such as rooms, how may are booked/available, types of rooms, if there's a gym), and the function becomes a method (being able to check the availability). 
     2. Objects contain keys which appear in a combination of key/value pairs. The key is used to access it's corresponding value.
     3. Literal notation: One way to create objects: variable is created (the object name), and within the variable in curly braces the key/value pairs are listed, one per line, with a comma at the end. At the end (still within the curly braces) is the method, which is another key, but the value is a function. For future uses, the values within the object (the keys) can be retrieved in future variables with dot (.) notation. For example, "hotel.name;"
     
   - **Chapter 5: "Document Object Model" (p 183-242)
     1.  DOM- "Document Object Model": Specifies how the browswer should interact with the HTML and JavaScript on a page. It is the in between, it uses a DOM tree which is made of objects and each one is a different part of the webpage. DOM is an API (Application Programming INterface) which allows programs talk to each other.
     2. DOM tree is a visual representation of all of the information that goes into the webpage. It shows where the attributes exist, where text resides, and which elements are related and where they go. You are able to access the DOM tree by get elements by their node.
     3. DOM queries- refers to accessing or updating an element, by "getElementById". You can retrieve elements using class, id, tags, or by actual element. Some of these retrieve multiple elements, while some retrieve a single individual element.
     4. There are two ways to selevt an element from a nodelist, which are the item() which will return an individual node from the nodelist, while the array syntax returns either one or multiple nodes from the nodelist. Once a nodelist has been created, a for loop goes through all the items in the list, which applies the same code to multiple elements.
     5. Nodes appear to be a different method of looking at code, as opposed to looking at the actual written code. It has siblings and parent elements, it still has whitespace, and can use the same CSS selectors utilized when styling the page, but it can also be more specific, acutally looking for specific text or a particular value.
     6. Programmer is able to change the text value within an element by using the "innerHTML" property to access specific content.
     7. When you have content that needs to be removed, the element must be stored in a variable, then removed by accessing the container element first, followed by the content to be removed
     8. XSS= Cross-site scripting: one way a person can attack a computer is by inserting unknown code into files. We are warned here to never open HTML from an untrusted source, make sure untrusted users are not able to submit markup or javaScript, and to always double check validations. Basically, if it's untrusted or you don't know where it comes from, check it thoroughly before allowing it on your page/computer. There are filters that can assist with prevention.
     9. Attribute nodes= once you access an element, you are able to add a .getAttribute to further narrow down what you are trying to access. Using this, you are able to change and remove attributes essentially the same way you remove an element.
   
