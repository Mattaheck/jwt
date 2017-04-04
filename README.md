# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT?
2. What information does each part contain?
3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/.



1. 3 parts of a JWT are the header, payload and signature

2. the header contains the type of token and the hashing algorithm being used.
the payload contains the claims.  reserved claims which are not mandatory but are suggested
public claims- which can defined by those using the JWTs
privated claims that contain information between parties that agree on using them

the signature is the the encoded header, encoded payload, the secret and algorithm specified in the header

3. JWT's are a good choice to be passed in HTML and HTTP environments
JWT tokens can be public/private in a form for signing.  signing with these tools offers less security holes.
they do not have natural document to object mapping 
