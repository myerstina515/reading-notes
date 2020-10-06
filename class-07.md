# Reading Notes: Class 7

## 1. Article

  - **Domain Modeling:**
    1. jgckvghb
    
    
## 2. HTML & CSS

  - **Chapter 6 “tables”
    1. A table puts information into a grid format, and every space in the grid is called a “table cell”. A table is created by using the “table” tag, and the cells are formatted into rows (tr tag), and the individual cells are separated by a “td” tag. 
    2. You can span columns and rows, depending on your formatting, if the information needs to be stretched to cover more than one position (i.e. time).
“thead”, “tbody”, and “tfoot” allow for the first and last rows to be different from the rest of the rows/columns.
    3. Width and spacing are able to be entered in the opening tag of the table, or the “th” tag, border and background are able to be added in the same location.

## JavaScript and jQuery

  - **Chapter 3 “Functions, methods, and objects” (p 106-144)**
    1. To retrieve or update values of properties, we can use dot notation or square bracket notation. There is also constructor notation, which is used as a template to have similar functions be able to access similar things, but in a simpler way by using “this.something”. The “this” can change to reflect each individual object. After the template is created, the developer is able to create a new variable with a name, then have it equal to the constructor function by placing each value into parenthesis, separated by a comma.
    2. “This” is a keyword to be used in functions and objects. It refers to the fact that it is calling information that is only available inside that particular function or object. Data can be stored in may places to be called on later, in variables, arrays, individual objects, and multiple objects.
    3. Built in objects include the browser object model (which has things like browser history, and built in tabs), document object model (makes a representation of the current page, and creates new spaces for each element), and global javascript objects (things that js language needs, such as days and times).
    4. The window object refers to the current tab of the browser, and contains lots of things that tell you about the browswer. It can tell you about the history, the location of the website, the height and width of the browser window, etc. There is also the document object, which has a list of commands that tells the user about specific qualities about the document itself, and can retrieve elements on the document (i.e.- get document.getElementById)). The commands help to access or create new elements onthe page without having to alter the HTML. There are also global objects (strings, numbers, booleans), and can be altered (i.e.- .length, .toUpperCase, .split).
    5. One other global object is date objects, which also encompasses time. The developer is able to retireve date, time, year, hour, milliseconds, and return as a string. It is even possible to adjust for timezone. An interesting tidbit is that when working with month, the months go from 0-11, rather than 1-12. Otherwise the nomenclature for hours and time, etc appear to follow military time, which most people are familiar with already.
    
    
