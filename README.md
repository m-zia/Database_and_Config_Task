# 📖 Minimalist Book Manager API

## Introduction

This is the starter repository for the Further APIs session. It provides a start to creating a Minimalist Book Manager API.

### Pre-Requisites

-   NodeJS installed (v18.12.1 Long Term Support version at time of writing)

### Technologies & Dependencies

-   [TypeScript](https://www.typescriptlang.org/)
-   [ExpressJS](https://expressjs.com/)
-   [Sequelize](https://sequelize.org/)
-   [SQLite3](https://www.npmjs.com/package/sqlite3)
-   [Jest](https://jestjs.io/)
-   [Supertest](https://www.npmjs.com/package/supertest)
-   [ESLint](https://eslint.org/)

### How to Get Started

-   Fork this repo to your Github and then clone the forked version of this repo

### Running the application

In order to run the unit tests run, firstly install the dependencies (if you haven't already done so)

```
npm install
```

Followed by:

```
npm start
```

### Running the Unit Tests

In order to run the unit tests run, firstly install the dependencies (if you haven't already done so)

```
npm install
```

Followed by:

```
npm test
```

### General Notes

- It is possible to manually write all of our database code, including manually writing SQL commands to execute, but it is
much easier and safer to use a library which abstracts over the database. Sequelize is one of the most popular JavaScript (and hence TypeScript) libraries for connecting to databases.

- A connection string is what it sounds like: a string which tells a database library how to connect to a particular database or server. These come in all shapes and sizes, depending on which kind of database we’re connecting to. You can find handy reference for many different types of connection string at ConnectionStrings.com

- https://sequelize.org/docs/v6/core-concepts/model-basics/


