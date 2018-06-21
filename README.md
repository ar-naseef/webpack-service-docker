# webpack-service-docker
webpack service in a docker

### reference
https://github.com/cerebral/webpack-packager <br/>
https://github.com/cerebral/webpack-dll <br/>
https://github.com/cerebral/webpack-sandbox <br/>
<br/>
https://github.com/cerebral/webpackbin <br/>

watch this for better understanding- https://www.youtube.com/watch?v=LWZHFcA9W6M

install `docker` & `docker-compose`
clone the project and start the docker by typing `docker-compose up --build`

this will start 3 node servers and a mongoDB server
port 4000 - webpack-sandbox
port 5000 - webpack-dll
port 5500 - webpack-packager

After spending more than a day to understand the code, I some how figured how the packages are bundled. Still couldn't find how the bundled code was used in webpack-bin.

here's a postman collection if it helps.
https://www.getpostman.com/collections/905a3ba6d19dd93face9

