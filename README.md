# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT?
  Header, Payload and Signature.
2. What information does each part contain?
  Header: JSON Object that typically consists of 2 parts.
    Type - JWT and the algorithm being used.
  Payload: JSON object that consists of user defined attributes - Public Claims
    Some attributes are defined in the standard - Reserved Claims
  Signature: The encoded header and payload, signed with a secret
3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/.
  1. Compact
  2. Easy to Sign
  3. Easy to Parse
