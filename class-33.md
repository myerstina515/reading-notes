# Context API

## Review, Research, and Discussion
  1. Describe use cases for useMemo() and useReducer(): `useReducer()` takes in three arguments and is better for managing state objects that contain multiple sub-values `useMemo` is a hook that memorizes the output of a function
  2. Why do custom hooks need the use prefix? By using the `use` prefix it makes it clear when a function needs to maintain all of the hook rules
  3. What do custom hooks usually do? Helps to make code more versatile and reusable, only storing things in it that you need it to store.
  4. Using any list of custom hooks, research and name one that you think will be useful in your applications: I think `useLocalStorage()` would be wonderfully helpful, as many apps want to have something kept in local storage, and it would be a standard way of doing so without having to look it up each time.
  5. Describe how a hook that fetches API data might work: `useFetch()` takes in the same information as a fetch call does, and is a quick way to set it up and provide state for `isLoading` 
  
### Vocabulary
  1. reducer: a function that determines changes to an application's state
  
## Context API

  1. Context provides a way to pass down information without having to rely on a top down method with props. It's designed to work for global information, such as the URL I created on my most recent lab. 
  2. Don't overuse, it can cause some issues with your hooks processing some information.

## Hooks and context example: "snackbar"
  1. A snackbar is a very lightweight piece of information that can pop up at the bottom of a page and not cause any issues with fucntionality. They are perfect examples of use for custom hooks. The state controlling them should be globally available, though the code is localized to one central component.
  2. Great component for Redux, and makes use of `useReducer` and `useMemo` as mentioned above.

## react context links
  * Bookmarked
  
  
