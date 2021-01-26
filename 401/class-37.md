# Redux - Combined Reducers
## Review, Research, and Discussion
  1. Why choose Redux instead of the Context API for global state? Redux is more helpful for larger projects, and makes it so the functions and state stay pure. Redux allows you to updateone piece of state, an having everything available globally helps for consistency/accessbility throughout the app.
  2. What is the purpose of a reducer? It determines changes in the application's state
  3. What does an action contain? Actions contain the payload, which is the information needed to change the state.
  4. Why do we need to copy the state in a reducer? When the state changes, the reducer creates a new object with the newly changed state.
  
#### Vocabulary
  1. immutable state: state that cannot be changed
  2. time travel in redux: an undo function that reverts the state to what it was prior to the action
  3. action creator: a plain function that returns an action object
  4. reducer: function that determines changes to an applications state
  5. dispatch: function of a Redux store. Only way to trigger a state change.
  
### Multiple Reducers Example
  1. Pull in `combineReducers` from redux allows the app to combine and use multiple reducers in one area.
  2. You then set ES6 default values for setting your default state values
  3. You'll get errors if a reducer doesn't return anything
  4. Make sure to only create a new object when there is a state change, don't every directly change or mutate the state.
