Example of node server for ES6 Resful API and webpack and docker

# Introduction
For this repository is about to setup Webpack with Nodemon & Babel inside Docker Container to improve performance for development on ES6 Node.js Server.

* [Medium] (https://medium.com/p/913db2cc73ed)

# Local configuration
* Install dependencies
```npm install```
* Start development live-reload server
```npm run dev```
* Start production server
```npm start```

# Docker configuration
* Build docker image from backend-serivce's .Dockerfile
```docker-compose build backend-service```
* Create docker container for backend-service and ready to have development server on port:9001
```docker-compose up backend-service```

## Authors
**Tanachot Techajarupan**
*ttanachot@gmail.com* - [LinkedIn](https://www.linkedin.com/in/tanachot-te/) - [Medium](https://medium.com/@ttanachot)