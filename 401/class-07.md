# Reading Notes Class 7

## Review, Research, and Discuss

  1. Write the following steps in the correct order:
    - Redirect to a third party authentication endpoint
    - Receive authorization code
    - Register your application to get a client_id and client_secret
    - Receive access token
    - Make a request to the access token endpoint
    - Ask the client if they want to sign in via a third party
    - Make a request to a third-party API endpoint
  2. What can you do with an authorization code? You can exchange it for an access token and is granted by the server granting authorization for an app.
  3. What can you do with an access token? It allows an application the ability to use an API.
  4. What’s a benefit of using OAuth instead of your own basic authentication? Requires stronger authentication and provides better security for the user. 
  
## Vocabulary:
  1. Client ID: Public identifier for apps
  2. Client Secret: A secret known only to you and the authorization server. Should never be displayed on anything that can be accessed publicly.
  3. Authentication Endpoint: used to interact with the resource owner and get the authorization to access the token.
  4. Access Token Endpoint: where the access token is received by the user making the request for the app 
  5. API Endpoint: A unique URL that is used to access the API information
  6. Authorization Code: A temporary code given to a client to later exchange for an access token to access the app.
  7. Access Token: A token that allows an application the ability to use an API.
  
## Preview
  1. Which 3 things had you heard about previously and now have better clarity on? Base64 seems a lot more simple now that it did in 201 when we had to utilize it for our project, OAuth makes a little bit more sense, and bcrypt.
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? insertBefore()/insertAfter(), OAuth, and testing! Always testing...
  3. What are you most excited about trying to implement or see how it works? I can't wait for the day that testing makes more sense to me.
  
## JSON Web Token
  - Bookmarked and ready to refer to
  - Compact, self contained method to transmit information safely to another party. They can be encrypted, but are considered to be very safe and secure way to transmit information. They are particularly helpful for: Authorization: Once the user uses JWT one time, each time thereafter it will be used as well. Information Exchange: JWT's can be signed, which adds another level of security and you can be sure the sender is who they say they are.
  - Header: has the type of the token and the algorithm being used. Payload: contains the claims. Signature: Verifies the user is who they say they are.
  - JSON is less verbose than other methods of tranmission, and there are parsers in nearly every major dev language, which makes them the most likely method of transmission to use. 









