# Class Notes

## Title

### Section 1[^1]

- REST stands for Representational State Transfer, which is designed around **resources**;
- The identifier of a resource is a URI that uniquely identifies that resource,(ex. `https://adventure-works.com/orders/1`);
- Common HTTP verbs include GET, POST, PUT, PATCH, and DELETE;
- URI's should be based on nouns, and NOT verbs. Example of a good URI is `https://adventure-works.com/orders`
- A "chatty"  web API exposes a larger number of small resources, whould should be avoided.
- Status codes overview: 
Successful GET: 200 (ok); or 200(no content)
Unsuccessful GET: 400
Successful POST: 200 or 204 (returns 409(conflict) if fails)
Successful DELETE: 204(no content)

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design