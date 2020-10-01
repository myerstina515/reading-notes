# Class 4 reading notes

## 1. HTML & CSS

   - **Chapter 4: Links**
     1. Links are inserted to the HTML document with the &lt;a&gt; tag. They can link to webpages, by placing the webpage in the opening tag, using an href to call the link, and can name it something by entering in text between the opening and closing tags. The text can be anything, and it will transform the text into a hyperlink. These are called absolute URL's, as you are accessing content that is not on your current website.
     2. There are also relative links, which take you to another page within your same webpage. Whether that's the main index page, or other files, such as a reviews page, or an about the company page. 
     3. You can also use links to send an email to someone (the owner of the page or company), and the target link to open the specified link in a new browser.
   - **Chapter 15: Layout**
     1. HTML elements are treated by CSS as if they are boxes, as discussed in previous reading "boxes". They can be block level or inline blocks (which flow inside of surrounding text. Multiple methods are used to position the elements. They can be kept in normal flow (on a new line), they can have relative positioning (able to be moved up/down/left/right, but does not effect surrounding elements), absolute positioning (where the element is in an area outside of the flow, and any text that appears behind it acts as if it does not exist), fixed position (also does not change surrounding elements, stays in the exact same space on the browser, despite any scrolling up or down the user does), and floating elements, which will be discussed on the next line.
     2. Floating elements are taken out of flow of the rest of the document, positioned in the top left or top right corner, and allows other content to wrap around it. Float is how blockquotes are able to appear inline with text wrapped around it, it's how columns and articles can appear on a front page. Multiple elements are floated, and they will appear one next to the other along the top, provided there is enough space.
     3. As technology had advanced, there are multiple different screen sizes to consider. Most developers create websites to be roughly 960-1000px wide so it is able to fit a wider variety of monitor sizes. Fixed layouts are more difficult to fit to different computer screens, as they primarily deal in pixels, while liquid layouts work better with the varying screen sizes currently, as they adjust based on percentages to better fit the varieties of screens.

## 2. JavaScript and jQuery
   - **Chapter 3: Functions, Methods, and Objects (only pages 86-99)**
     1. Functions are statements that are grouped together to pertain to a specific task. The developer adds parameters, which are passed to the function. Later, when the function is called, you are asking it to perform it's task. The task it performs (or the information it provides once called) is called the return value. 
     2. Though there is a significant amount of information in a function, it does not give the information to the user until it is called. You musc declare a function (give it the information) before it can be called. 
     3. Functions can return words, but they can also make calculations if provided numbers. 
     4. Functions can store more information by using an array to hold the information, then multiple 'calls' can occur from the array.
     
## 3. Article: 6 Reasons for Pair Programming
   - **Notes:**
     1. Paired programming is utilized at code fellows to encourage collaboration with other coding students. It helps to have immediate feedback, and another set of eyes to bounce code off. It helps to work on listening skills, ability to discuss code with correct language, and ability to read code.
     2. Pair programming is more efficient in the long run, due to catching bugs and errors in real time, instead of going back and having to find errors. It also is more engaging than individual programming, as you have another person to keep you paying attention and involved in the process, where otherwise you could become distracted by other non-programming activites.
     3. Not only does pair programming help to share knowledge with another person, it can improve confidence with coding and explaining though processes. Employers also want to hire folks that are able to engage with other teammates on projects and have the social skills that requires.
     4. Pair programming in school helps to prepare students for pair programming exercises in job interviews, which some employers use to assess if the candidate is a team player and can interact appropriately on their team. Which many new companies have new grads participate in pair programming to improve coding skills with team members already accustomed to programming.
