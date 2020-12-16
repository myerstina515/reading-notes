# Access Control (ACL)

## Review, Research, and Discussion

  1. When is Basic Authorization used vs. Bearer Authorization? Basic authentication makes use of a username and a secret, while bearer authorization makes use of a token as well that provides increased security.
  2. What does the JSON Web Token package do? JWT is a standard used to create access tokens for bearer authorization
  3. What considerations should we make when creating and storing a SECRET? You need to consider that the secret should only be known by the two parties involved in the authentication and should be encrypted. You should also be aware that it is able to be intercepted and decrypted.
  4. Vocabulary:
    - encryption: converting information into a secret code that hides the informations meaning.
    - token: ensures each request is validated for authenticity and signed.
    - bearer: a bearer token is a string of encrypted values that is exchanged between server and host to confirm identity and access.
    - secret: they allow you to store sensitive information in you database, and are only known by the server and the user, and are encrypted.
    - JSON Web Token: JWT creates access tokens for bearer authorization.
    
## Preview
  1. Which 3 things had you heard about previously and now have better clarity on? tokens, OAuth, base 64 encryption
  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? testing, additional security features for JWT, and how yml files work.
  3. What are you most excited about trying to implement or see how it works? I'm starting to understand testing a little bit, and am excited for more information.

## RBAC- Video
  - Role Based Access control: your access depends on your role in the organization. 
  - What roles do I have in my system. For each role, what do they need access to? read/write access. Users that authenticate themselves have certain access.
  - Users are enrolled as one or more roles that dictate access based on need-to-know.
  - Benefits: Policy doesn't need to be updated with staffing changes, policies are static. When new employees are hired, their access is dictated by their role and function/job requirements. Controls access to information and improves security.
    
  
## 5 Steps to RBAC
  1. Inventory your systems- figure out what information/resources need to be restricted to limited access.
  2. Analyze your workforce and create roles- basic user/customer service/database administrator all require different access to do their jobs
  3. Assign people to roles- figure out what defined roles each employee belongs in.
  4. Never make one off changes- If you do this, your system will unravel quickly
  5. Audit- periodically check to make sure your list of employees only has access to the roles they are supposed to be categorized in.
  
## Wiki
  - RBAC utilized by most companies with 500+ employees, and addresses many needs of governemnt organization needs as well. Role Assignment, Role authorization, and permission authorization are the three primary rules. There are 3 levels of standardization including:
    1. core RBAC
    2. hierarchical RBAC - adds support for inheritance
    3. constrained RBAC - adds separation of duties
  - widely accepted as best practices in the tech field, and with analysis has shown to improve employee productivity and decrease downtime.
  
  
  
  
  

    
