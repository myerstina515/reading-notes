# Reading Notes Class 8

## 1. HTML & CSS

  - **Chapter 7 "Forms" (p 144-175)**
    1. A "form" is an area for the user to input informataion. There are many "forms" in HTML, including a textbox, a password box, a text area (larger than a box, has multiple lines), all for adding text. Users can make choices via checkbox, radio buttons, and drop down boxes. And forms can be submitted by pressing submit buttons, image buttons, and a file upload box. The forms take the submitted information and store them in the database. One thing to keep in mind with radio buttons, they cannot be deselected, only have the selection changed. So if it's a situation like a person agreeing to something, a checkbox is better because it can be selected and deselected.
    2. There are hidden controls that can hide text or input from the user, but the author would be able to see it, which we will likely be using soon to hide the link to the sales.html page from the main index.html pageo n our salmon cookies project.
    3. A fieldset is an element that can group multiple input elements into one block on the screen, with a "legend" as a label. It is possible to require a box be filled in before the user can submit the form. That validation check can also check to make sure a date is valid, an email/URL is valid, and the search input is populated.
    
  - **Chapter 14 "Lists, Tables, and Forms" (p 330-357)
    1. There are many different alterations one can do in CSS to tables and lists. The bullet points can change shape/color, the numbers and alpha  can be changed to different character types, and even images can replace bullet points. Bullet point positioning can be inside (inline), or outside (text does not come back underneath the dot). 
    2. Tables can be altered in many ways as well, by changing backfround color of alternating rows, change the text appearnce, change the borders, give or take away padding from cells, and align text. There are a bunch more options of table adjsutments that can be done online. The border of empty cells can be removed, gaps between cells can be altered, 
    3. Things can be alterted for all inputs in similar ways to which text and normal elements can be with some slight differences. All of the colors and alignments, borders/margins/padding, shadow, etc can be adjusted. With buttons, they also have a hover function that can be added that changes the color of the button when the mouse is hovered over the element.
    
# 2. JavaScript

  - **Chapter 6: "Events" (p243-292)
    1. There are many events that can happen in the web browswer to trigger a javascript function. Three steps are knows as event handling, and are involved ing etting it to trigger the JS code. 1) select element 2) specify event and 3)call code. There are three different event handlers, one in HTML (which is thought of as bad practice) that would respond to the events. Now HTML does not do any of the interactivity. There are also traditioanal DOM event handlers, and DOM level 2 listeners. Each one handles the events in a slightly different way, and the third one is the newes, which allows one event to trigger multiple different functions.
    2. Event listeners are the newest methods of event handlers, and they allow one event to trigger multiple different functions as discussed above. With handlers and listeners parameters are needed.
    3. EVent flow matters, but really only does when you have handlers on an element as well as one of it's ancestors or descendant elements. The flow has event bubbling where it begins with the most specific node and flows outward to the lease specific (the ancestor elements), while event capturing begins with the least specific and flows inward (to the descendant elements). The event object tells you all the information about the event, including what key was pressed, what arguments need to be passed, etc. 
    4. EXamples of events tracked are mouse events, button clicks, any keyboard events and what keys were pressed, form events and what was submitted/changed/input, mutation events, and HTML5 events (content downloaded, hash changes, etc) to name only a few examples. 
    
    
    
