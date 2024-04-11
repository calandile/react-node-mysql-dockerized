# react-node-mysql-dockerized
Building a React App that connects to MySQL via NodeJS using Docker

## Installation
Pull the images and build the containers:
```
  cd react-node-mysql-dockerized
  docker-compose build
  docker-compose up -d
```
 To check which containers (with images) are running, use the command:
 ```
 docker ps
 ```
Any server issues are resolved with:
```
cd server
yarn install
```
Now that the images are running in containers, open your browser and navigate to: 
```
http://localhost:3000
```

### Known issues
To install yarn on WSL2 run:
```
curl -o- -L https://yarnpkg.com/install.sh | bash
```