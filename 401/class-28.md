# Component Composition

## Review, research, and discussion

  1. Can a parent component access the state of a child component? yes, by using a callback function on the child and parent element that passes the information back to the parent.
  2. What can be passed along in a prop variable? Pretty much any type of data that is found in the app.
  3. How can a child component “know” the state of another component? Using a hook in react
  
### Vocabulary

  1. component props: Props are properties that can be passed along to child elements in a react app
  2. component state: the state is referred to in the constructor of a component. It is the "snapshot" of what is happening in the component at that particular moment in time.
  3. application state: the "snapshot" of what is happening in the entire app at that particular moment in time. It is referred to in the constructor of the app page, where all of the components report their data to.
  
## Preview

  1. Which 3 things had you heard about previously and now have better clarity on? After lecture today I had a better understanding of states, components, and parent/child components.
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? More info on linking the components, how to filter what data goes where, and testing.
  3. What are you most excited about trying to implement or see how it works? I'm looking forward to working on the remainder of the routes.
  
### React Basics
  1. Component lifecycle: Three stages including mounting, updating (if indicated), and unmounting.
  2. Other lifecycle methods: Include forceUpdate, getDerivedStateFromError.
  3. Higher order components: A function that takes a component and returns a new component. 
  4. React state and setState(): asynchronous, and the only way you should change state in react.
  5. React context: global state for components. 

### props.children
  1. this.props.children: what to use when you don't know what the component's children are ahead of time. 

### composition vs inheritance
  1. Also talks about the generic reference to props.children

### react testing library api example
  1. An example of a full testing suite that is now bookmarked (as are the next two reference pages:

### react if-component

### react testing library async
  
  
  
  
  
  
  
  
  
  
