# JWT Basics
JWT stands for JSON Web Token, which is a type of token that is used for securely transmitting information between parties in a compact and verifiable way. JWTs consist of three parts: a header, a payload, and a signature.

The header typically contains information about the algorithm used to sign the token, while the payload contains the actual information that is being transmitted, such as user details or authorization claims. The signature is used to ensure that the token has not been tampered with or modified during transmission.

JWTs are commonly used in web applications as a means of authentication and authorization. When a user logs in to a web application, the server generates a JWT and sends it back to the client. The client can then include this token in subsequent requests to the server, allowing the server to verify the user's identity and authorize access to protected resources.

JWTs are often used in combination with OAuth 2.0 and OpenID Connect protocols to enable secure and standardized authorization and authentication flows.
# To run this project
```
npm start
```
