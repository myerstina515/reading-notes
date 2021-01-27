# Redux - Asynchronous Actions
## Review, Research, and Discussion
  1. How granular should your reducers be? default solution would be that a change of any of those attributes would trigger a separate kind of action such as CHANGE_EMAIL or CHANGE_NAME. And sometimes such granularity is good and valuable because different reducers, different parts of your application might need to react differently to those actions ["how granular are your redux actions?"](https://reactkungfu.com/2016/11/how-granular-are-your-redux-actions/)
  2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched: Pro AND con. Pro because it can decrease the amount of code that needs to be written and can help to simplify the same. Con because it is easy to get confused between what code is attached to what pages, especially when the action has a common name.
  3. Name a strategy for preventing the above: Separate the actions so each one calls a separate reducer.
#### Vocabulary:
  1. store: an immutable object tree in Redux. It is a container that has the initial state and later iterations of the state.
  2. combined reducers:An object whose values come from different bits and pieces of state. Different reducers are held in different areas of code, and are brought together by a combined reducer.
  
## Dan Abramov Video
![link](https://www.youtube.com/watch?v=6g3g0Q_XVb4)
Broken link

## Async Logic and Data Fetching
  1. Redux middleware allows us to write logic with side effects (`useEffects`)
  2. Thunk middleware is the offical API fetching of Redux, and allows us to write things like `dispatch` and `getState`
  3. "Thunk" means "a piece of code that does some delayed work". 
  
## Thunk Middleware
  1. Bookmarked [here](https://github.com/reduxjs/redux-thunk)
## Redux Thunk
  1. Also bookmarked for the code examples [here](https://www.digitalocean.com/community/tutorials/redux-redux-thunk)
