# express-react-example
create-react-app with an express backend
## REQUIREMENTS
I use [Yarn](https://yarnpkg.com/en/) but you can use NPM analagously.
## INSTALLATION
```
cd into dir
yarn install
node server.js
```
in another shell:
```
cd client
yarn install
yarn start
```
navigate to localhost:3000

All requests from the client are proxied to localhost:5000 (where the express server lives).