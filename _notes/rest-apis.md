# REST APIs

REST (Representational State Transfer) is an architectural style for designing networked applications. APIs that adhere to the principles of REST are called RESTful APIs.

## Constraints

- **Client-Server:** Separation of concerns.
- **Stateless:** Each request from a client contains all the information needed to service the request.
- **Cacheable:** Responses must define themselves as cacheable or not.
- **Layered System:** A client cannot ordinarily tell whether it is connected directly to the end server or to an intermediary along the way.

REST has been the de-facto standard for building APIs for many years. [[fastapi]] is a great tool for building REST APIs. It is often compared with [[graphql]].
