# Auth-jwt
Creating a NodeJS Authentication application with Json Web Token and BCrypt for hashing password during authentication of users in a web app. [configuring MongoDB as the database engine]!

## Initializing Node Package Manager
- Run `npm init (-y)` to initialize Node

## Dependencies & DevDependencies to install in NPM
- `npm i expresss` to install express
- `npm i --save-dev nodemon` as the restarter of the server
- `npm i mongoose` to install the MongoDB database package or dependency
- `npm i dotenv` to install the dotEnv file for creating environment variables as storing passwords in them
- `npm i @hapi/joi` to install the joi dependency for validation of users data
- `npm i bcryptjs` to install BCrypt that will hash passwords and hide it from the public
- `npm i jsonwebtoken` to install JWT to verify successful authenticated users

## Creating the app entry file
- creating an `index.js` file for entry into the application