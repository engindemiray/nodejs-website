## Web development with Node.js

![nodejs-website-image](https://user-images.githubusercontent.com/91262816/198351584-06a8758e-27d0-4062-855e-e3f7aac33423.png)

## Languages & Tools

- JavaScript
- Node.js
- Express.js
- EJS
- Bootstrap
- MySQL

## Installation
Run these commands in Terminal

To install package.json:
``` bash
$ npm init --yes
```
To install Express:
``` bash
$ npm i express@4.18.1
```
To install nodemon:
``` bash
$ npm i nodemon -g
```
To install EJS (Tamplate Engine):
``` bash
$ npm i ejs
```
To install Bootstrap:
``` bash
$ npm i bootstrap@5.2.2
```
To install MySQL:
``` bash
$ npm i mysql2@2.18.1
```
To start the app:
``` bash
$ nodemon index.js
```
❗[nodemon] app crashed - waiting for file changes before starting...❗<br/>
When you start your server with nodemon, you might face this error. Solution:
``` bash
$ npm install --save mysql2
```

## MySQL Database

![mysql-database-image](https://user-images.githubusercontent.com/91262816/198361239-598f6464-045b-4731-94ab-a3da10409bbd.png)

Write your MySQL password:
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
