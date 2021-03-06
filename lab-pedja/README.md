401 JS --  Lab 37+38 Full Stack Crud App
===

## Features
> Purpose of this lab is practice creating async actions for making ajax calls to our server and adding simple AUTH that will allow USER to signup/login to Sluggram RESTful API server. Lab 38 feature are user profile creation and updating. Lab 40 feature are connecting second model - photos and ability to upload photos to your AWS S3 data storage.

## Code Style
* Javascript ES6, JSX


## Tech / framework used

* Webpack
* React
* Redux
* Redux-devtools
* Babel
* sass
* NodeJS
* Express
* MongoDB
* AWS
* Superagent
* Jest
* Cors

## Installation and How To Use

  * Fork || clone this repo to you computer

  * Run `yarn`

  * Setup your .env file in backend folder

  ```
  PORT=<ADD PORT>
  DEBUG=true
  CORS_ORIGINS=http://localhost:8080
  MONGO_URI=mongodb://localhost/testing
  SECRET=<ADD YOUR SECRET STRING>
  AWS_ACCESS_KEY_ID=<'ADD YOUR AWS KEY ID'>
  AWS_SECRET_ACCESS_KEY='ADD YOUR AWS ACCESS KEY'
  AWS_BUCKET='ADD YOUR AWS BUCKET NAME'
  ```

  * Setup your .env file in frontend folder

  ```
  API_URL=http://localhost:PORT
  CDN_URL=/
  NODE_ENV=debug
  ```

  * Run mongoDB with `yarn dbon` command

  * Start server with `yarn start`

  * Run webpack command `npm run watch`. After build has been completed - webpack-dev-server will show provide URL where your project is hosted. Copy that address to your browser to view app features

  * Perform user signup/login  
  
  * 

### Credits
REST API used for backend `https://github.com/slugbyte/sluggram` 

### Licence
MIT © Pedja Josifovic 401 JS 
