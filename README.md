# serviceo-auth

Auth0 authentication for serviceo applications.


## Usage instructions

1. Register provider inside `start/app.js` file.
const providers = [
  'serviceo-auth/providers/ServiceoAuthProvider'
]

2. Register middleware inside `start/kernel.js` file.
const namedMiddleware = {
  auth0: 'Serviceo/Middleware/Auth'
}

3. Configure `AUTH0_SECRET` key in .env file.