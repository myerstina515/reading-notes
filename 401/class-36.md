# Application State with Redux
## Review, Research, and Discussion
  1. What are the advantages of storing tokens in “Cookies” vs “Local Storage”: Local storage is more vulnerable to hackers, and local storage is accessible in the dev tools on the webpage, while cookies are more secure.
  2. Explain 3rd party cookies. A 3rd party cookie is a cookie that is set on a website other than the website owner to get additional information about customers/users to target marketing.
  3. How do pixel tags work? Also called marketing pixels, they are a tiny 1x1 px graphic that collects user data about visitors on a website to get more inforamtion about what they look at and what they do on your site.
  
#### Vocabulary:
  1. cookies: similar to local storage but more secure, it can make the website remember you between visits so the website takes less time to render and the website can remember what you do when you visit.
  2. authorization: Basic and Bearer, it requires password and username to be entered correctly to be able to access the stored information on the site.
  3. access control: Controls what employees have access to what information and what they can do with it. Standardizes the dispersal of information so people with the same title have access to the same abilities.
  4. conditional rendering: "this information displays if these conditions are met" for example, if username and password are entered properly, it will render the user page as well as a 'logout' button, otherwise it will not.
  
### Dan Abramov Redux Tutorials
1. Everything that changes in an app is contained in a single object called the state, or state tree
2. The state tree is redundant. You cannot modify it. Any time you want to change the state, you have to dispatch an action.
3. Pure functions: return value depends solely on the arguments -- no observable side effects -- predictable and replicatable. Redux functions must be pure.
4. Function must take in previous state and return the new state
5. Remaining videos are broken, docs were reviewed as noted in 401 slack channel - via Lena
