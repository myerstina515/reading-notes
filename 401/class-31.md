# Hooks API

## Review, research and discussion
  1. Why do we not need more .html pages in a multi-page React app? We are able to use a browser router to route to different pages and contain specific information passed through from the props or created on that page.
  2. If we wanted a component to show up on every page, where would we put it and why?
    A. Outside the <BrowserRouter/> (I believe it's this one. BrowserRouter tag links it to a specific route, so if it were placed outside of this, it would show up on every route described by routers.
    B. Inside the <BrowserRouter />, outside a <Route />
    C. Inside a <Route />
  3. What does props.children contain? props.children contains anything that;s included between the opening and closing tags.
  
### Vocabulary
  1. Composition: where a more “specific” component renders a more “generic” one and configures it with props
  2. Children / Child Components: components that only contain what is passed from the parent components via props
  3. Hash Routing: use of a hash symbol in the url to route to the appropriate page
  4. Link Routing: the user clicking on a link to be routed to the appropriate page
  
## Preview
  1. Which 3 things had you heard about previously and now have better clarity on? routes, browser routing, props.children
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? routing, hooks (easier routing/populating of the page), testing in react
  3. What are you most excited about trying to implement or see how it works? still waiting to get to the testing portion of the assignments
  
## Making sense of hooks
  1. Logic is stateful, and it's difficult to break down componenets down any further than they already are. So we are left with huge components, complex patterns, and duplicated logic. Hooks help us to organize the logic into reusable units.
  2. At first, it can appear to bloat code, but if used properly and in large projects/components, it can actually simplify and decrease the size of the code.
  3. React keeps the state for hooks in the same place as it keeps the state for classes. It has an internal update queue regardless. 
## State hook
  1. Hooks don't work inside of classes, but they can work instead of classes.
  2. A hook is a special feature that lets you hook into react features. Usestate is a way to make sure variables declared inside functions are able to be used outside of the functions. 
  3. When reading state with a hook, you are able to call the state directly without using "this.state.count" you're able to just use "count".
  
## Hooks API
  1. Hooks return a pair: the initial state and the current state.
  2. Useeffect can be used for updating a friend's online status in a chat server.
  3. Hook rules: Only call hooks at top levels, not inside loops, conditionals, or nested functions. Only call hooks from react functions, not from regular javascript functions. 
  4. Custom hooks will begin with "use" and will call in other hooks. Can be used for many different things such as animations or clocks.

## Hooks API reference:
  1. [bookmarked](https://reactjs.org/docs/hooks-reference.html)
  
## Effects hook
  1. Lets you perform side effects in function components
  2. Effects without cleanup: they can be used and forgotten about, without having to do anything additional after use.
  3. Able to be updated with each render: Lets us read the value before it goes 'stale' 
  4. Important to use multiple effects to separate concerns and make the functions pure
  
  
  
  
  
  
  
  
  
  
  
  
  
  
