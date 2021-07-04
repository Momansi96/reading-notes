# Class11  

[Return to home page](https://momansi96.github.io/reading-notes/). 


## OAuth

* What is OAuth?

OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. 

* Give an example of what using OAuth would look like.

The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.

* How does OAuth work? What are the steps that it takes to authenticate the user?

- The following happens :

 1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
 2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
 3. The first site gives this token and secret to the initiating user’s client software.
 4. The client’s software presents the request token and secret to their authorization provider. 
 5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
 6. The user approves a particular transaction type at the first website.
 7. The user is given an approved access token .
 8. The user gives the approved access token to the first website.
 9. The first website gives the access token to the second website as proof of authentication on behalf of the user.
 10. The second website lets the first website access their site on behalf of the user.
 11. The user sees a successfully completed transaction occurring.

* What is OpenID?

OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans.


## Authorization and Authentication 



* What is the difference between authorization and authentication?

Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource

* What is Authorization Code Flow?

which exchanges an Authorization Code for a token. Your app must be server-side because during this exchange, you must also pass along your application's Client Secret, which must always be kept secure, and you will have to store it in your client.

* What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

The PKCE-enhanced Authorization Code Flow introduces a secret created by the calling application that can be verified by the authorization server; this secret is called the Code Verifier. Additionally, the calling app creates a transform value of the Code Verifier called the Code Challenge and sends this value over HTTPS to retrieve an Authorization Code

* What is Implicit Flow with Form Post?

which is intended for Public Clients, or applications which are unable to securely store Client Secrets. While this is no longer considered a best practice for requesting Access Tokens, when used with Form Post response mode, it does offer a streamlined workflow if the application needs only an ID token to perform user authentication.

* What is Client Credentials Flow?

For this scenario, typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow, in which they pass along their Client ID and Client Secret to authenticate themselves and get a token.

* What is Device Authorization Flow?

With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device

* What is Resource Owner Password Flow?

which requests that users provide credentials (username and password), typically using an interactive form. Because credentials are sent to the backend and can be stored for future use before being exchanged for an Access Token, it is imperative that the application is absolutely trusted with this information.
