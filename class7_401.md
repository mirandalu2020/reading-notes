# Class Seven Notes (401)

## Bearer Token

### JWT Intro[^1]

- JWT is an open standard that defines a compact and self-contained way for securely transmitting info between parties as a JSON object
- JWT tokens are useful when an aurotization is required, or when info exchange security is required
- The payload of JWT contains claims, which are statements about an entity and additional data.

### JWT Security[^2]

- It's secure because both the sender and the receiver have to know the layload and secret in order to calculate the hash. If a third party wants to change the content, the hash will no longer match and the receiver will know the content has been altered.

### Why use JWT[^3]

- We use JWT because the info would be signed and verified.
- JWT is compact and self-contained, which is useful because it can now be sent via URL in a POST request as an HTTP header, and the token itself contains info about the user. This allows for fast transmission and avoids querying the database more than once.
- The three compoennt of a JWT signature are: the header, the payload, and the signature. The header includes the algoritm and type (JWT, 64-base url encoded), the payload includes the claims (user details), which is also base64url-encoded, and signature, which contains encoded header and payload with secret. If the payload is changed without knowing the secret,the signature will no longer match.

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://jwt.io/introduction/
[^2]:https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure
[^3]:https://www.youtube.com/watch?v=926mknSW9Lo