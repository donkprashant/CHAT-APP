# Snappy - Chat Application 
Snappy is chat application build with the power of MERN Stack. 

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.
### To Run App

install the dependencies
```shell
cd chat-react-app-react-nodejs
cd server
yarn
cd ..
cd public
yarn
```
 start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```
Now open localhost:3000 in  browser.

#### Second Method
- This method requires docker and docker-compose to be installed in  system.

```shell
docker compose build --no-cache
```
after the build is complete run the containers using the following command
```shell
docker compose up
```
now open localhost:3000 in your browser.