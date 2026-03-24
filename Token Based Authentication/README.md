This authentication flow demo demonstrates a token-based authentication workflow using Postman to authenticate a user, retrieve a token, and make authorized API requests.

The flow uses the ReqRes API to simulate user login and protected resource access:

- Authenticate with email and password to obtain a session token
- Store the token in environment variables
- Use the token in subsequent requests via Bearer authorization
- Include dynamic data (timestamp) via pre-request scripts
