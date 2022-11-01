# Testing app for Express REST API & Docker

## Links
https://medium.com/@onejohi/building-a-simple-rest-api-with-nodejs-and-express-da6273ed7ca9
https://github.com/fireship-io/docker-nodejs-basic-demo

## To Run in Docker
    docker build -t testapi:1.0.0 .
    docker run -p 3000:3000 testapi:1.0.0
    open in a browser: http://localhost:3000/url

## To Run on local machine 
    npm install
    npm start (or use node ./app.js)
    (or use forever to run in background if you have that installed) forever start ./app.js