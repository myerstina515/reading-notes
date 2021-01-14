# Routing

## Review, Research, and Discussion
  1. Do child components have direct access to props/state from the parent? Child components have access to props that are passed from the parent element to the child element. Any "state" is only accessible on it's own page (if created on it's page) or it's parent page.
  2. When a component “wraps” another component, how does the child component’s output get rendered? They render based on the state that is passed to them from the parent.
  3. Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application? It can be as long as the correct props is passed to the other page.
  4. What trick can a parent use to share all props with it’s children? By using "spread" notation
  
### Vocabulary
  1. props.children: Used when you are referring to child elements that don't yet exist.
  2. composition: where a more specific component renders a more generic one and configures it with props
  
  
## Preview
  1. Which 3 things had you heard about previously and now have better clarity on? props vs state and when each can be called, wrapping components, react language in general
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? understanding testing better, props.children, and spread notation
  3. What are you most excited about trying to implement or see how it works? going over linking the different routes up to API's. Making the code more general to work with various API's easily.
  
