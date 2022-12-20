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

Install npm packages:
``` bash
$ npm install
```
Run the app with this command:
``` bash
$ nodemon index.js
```
You may visit the application on browser with the URL: http://localhost:3000

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
