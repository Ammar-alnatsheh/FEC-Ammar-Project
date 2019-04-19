# FEC-Ammar-Project

> This Project is the Front-End-Capstone for Hack Reactor bootcamp
> in this repo my responsibility is to build a component that can read
> from a database records of reviews and display them as a grubhub style
> with slightly different style.

## Related Projects

  - https://github.com/HRSF108-Group7/FEC-profile
  - https://github.com/HRSF108-Group7/FEC-menu
  - https://github.com/HRSF108-Group7/FEC-suggestion

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

in the URL use /restaurants/:id to check the restaurants review.
fake information has been used using faker framwork.

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node 6.13.0
- React 16.7.0
- React-dome 16.7.0
- MySql 2.14.1
- Body-parser 1.17.2
- Express 4.15.4
- JQuery 3.2.1

for development enviroment 
- @babel/core 7.2.2
- @babel/preset-env 7.2.0
- @babel/preset-react 7.0.0
- babel-core 7.0.0-bridge.0
- babel-jest 23.6.0
- babel-loader 8.0.4
- enzyme 3.8.0
- enzyme-adapter-react-16 1.7.1
- faker 4.1.0
- jest 23.6.0
- morgan 1.9.1
- react-svg-loader 2.1.0
- regenerator-runtime 0.13.1
- webpack 2.2.

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install
npm install -g webpack
npm run create-db
npm run seed-db
npm run test
npm run react-dev
npm start
```

### Installing Database
[MySQL](https://dev.mysql.com/downloads/installer/).
```sh
Modifiy the username and password after installing MySQL in /database/config.js file
```

### Installing Docker
[Docker](https://docs.docker.com/v17.12/install).
```sh
To build an image use docker-compose build
To run the docker-compose image use docker-compose up
To seed the database in the URL type /reviews/seed
```
