# Jobly Backend

## About the Project

Jobly is a web application designed for job seekers to find and apply for job listings. This repository houses the server-side code written in Node.js, utilizing a PostgreSQL database and numerous npm packages including Express.js, bcrypt, jsonwebtoken, among others.

This project includes both a frontend and backend, with this repository focusing on the backend. The application is deployed on Heroku for public access.

- [Backend on Heroku](https://jobly-backend.herokuapp.com/)
- [Frontend GitHub Repository](https://github.com/behnamsaba/jobly-frontend)
- [Live Project](http://equal-frog.surge.sh)

## Installation

First, clone this repository:

```bash
git clone https://github.com/behnamsaba/jobly-backend.git
cd jobly-backend



## Usage

The following npm scripts are available:

- `npm start`: Starts the server using node.
- `npm run dev`: Starts the server using nodemon for automatic reloading.
- `npm test`: Runs tests using Jest.

## Configuration for Tests

Jest has been configured to ignore certain paths during testing:

- `/node_modules/`
- `config.js`

## Dependencies

This project uses the following dependencies:

- bcrypt: ^5.0.0
- body-parser: ^1.19.0
- colors: ^1.4.0
- cors: ^2.8.5
- dotenv: ^8.2.0
- express: ^4.17.1
- jsonschema: ^1.2.6
- jsonwebtoken: ^8.5.1
- morgan: ^1.10.0
- pg: ^8.3.0

This project also has the following dev dependencies:

- supertest: ^5.0.0-0
