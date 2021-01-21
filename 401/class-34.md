# `<Login/>` and `<Auth/>`

## Review, Research, and Discussion
  1. Why is the Context API useful? Context API is useful because it can help to make information globally available in the app rather than having to pass it in props to each individual child element.
  2. Can a component outside of a provider get its context? Yes, any component inside the app can get the context as long as it is passed properly and imported at the top of the target page.
  3. What are some common use cases for using the Context API? Needing to pass functions that need to be available in mutiple places.
  4. Describe “Context Hell”: As far as I can find, it has to do with too many nested contexts.
  
### Vocabulary
  1. global state: state that is accessible at the top level of the app and passed via props
  2. global context: context that is passed from the app.js component and is available to all child componenets
  3. provider: React uses provider pattern in Context API to share data across tree descendants
  4. consumer:  consumer takes a child as a function and that function returns a node
  
## what is role based access control?
  1. It restricts network access based on a person's role within an organization
  2. You can designate management or employee roles that allow certain privileges.
  3. Having roles reduces administrative work, as a new employee can be assigned automatically by job title/function, and can decrease unneccessary access to sensitive information/documents.

## react-cookies component
  1. React's way of using and saving cookies
  2. [Bookmarked](https://www.npmjs.com/package/react-cookies)
  
## react cookie library
  1. [also bookmarked](https://www.npmjs.com/package/react-cookie)
