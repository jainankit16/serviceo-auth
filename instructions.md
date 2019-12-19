## Register provider & middleware

Register provider inside `start/app.js` file.

const providers = [
  'serviceo-auth/providers/ServiceoAuthProvider'
]


Register middleware inside `start/kernel.js` file.

const namedMiddleware = {
  auth0: 'Serviceo/Middleware/Auth'
}