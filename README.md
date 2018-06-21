# webpack-service-docker
webpack service in a docker

### reference
https://github.com/cerebral/webpack-packager <br/>
https://github.com/cerebral/webpack-dll <br/>
https://github.com/cerebral/webpack-sandbox <br/>
<br/>
https://github.com/cerebral/webpackbin <br/>

watch this for better understanding- https://www.youtube.com/watch?v=LWZHFcA9W6M <br/>

install `docker` & `docker-compose` <br/>
clone the project and start the docker by running `docker-compose up --build` <br/>

this will start 3 node servers and a mongoDB server<br/>
port `4000` - webpack-sandbox <br/>
port `5000` - webpack-dll <br/>
port `5500` - webpack-packager <br/>

After spending more than a day to understand the code, I some how figured how the packages are bundled. Still couldn't find how the bundled code was used in webpack-bin. <br/>

here's a postman collection if it helps. <br/>
https://www.getpostman.com/collections/905a3ba6d19dd93face9 <br/>

