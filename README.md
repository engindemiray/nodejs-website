# Web Development with Node.js

![nodejs-website-image](https://user-images.githubusercontent.com/91262816/198351584-06a8758e-27d0-4062-855e-e3f7aac33423.png)

## Tech Stack

- JavaScript
- Node.js
- Express.js
- EJS
- Bootstrap
- MySQL

## Installation

Creating a package.json file:
``` bash
$ npm init --y
```
Install Express, EJS and Bootstrap with this command:
``` bash
$ npm i express ejs bootstrap
```
Install MySQL2 with this command:
``` bash
$ npm install --save mysql2
```
Install nodemon with this command:
``` bash
$ npm i nodemon -g
```
Run the app with this command:
``` bash
$ nodemon index.js
```

## MySQL Database

![mysql-database-image](https://user-images.githubusercontent.com/91262816/198361239-598f6464-045b-4731-94ab-a3da10409bbd.png)

Type your MySQL password:
```js
const config = {
    db: {
        host: "localhost",
        user: "root",
        password: "********",
        database: "nodedb"
    }
}

module.exports = config;
```
