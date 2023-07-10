# NodeJS Authentication App
> A complete authentication app with login, logout, register, forget password, email verification(for added security), and access control. Can be used as starter for other Node.JS applications. using Node.js, Express, Passport, JWT, Mongoose, and more. 



![Screenshot (4)](https://user-images.githubusercontent.com/49118089/90341145-b776a900-e01a-11ea-93c8-4f6864a141c1.png)

## Technologies Used
1.  NodeJS
2.  Express
3.  EJS
4.  MongoDB
5.  Mongoose
6.  PassportJS
7.  JWT
8.  Nodemailer


## Prerequisites
- Git
- NodeJS
- CLI

## Installation

##### Clone the latest Repository

`

##### Into the project directory

`cd nodejs-auth`

##### Installing NPM dependencies

`npm install`

##### Then simply start your app

`npm start`

#### The Server should now be running at http://localhost:8000/

## Folder Structure

nodejs-auth <br>

├── config <br>
│ --- ├── kue.js <br>
|   --├── middleware.js <br>
│ --- ├── mongoose.js <br>
│ --- ├── nodemailer.js <br>
│ --- └── passport-goggle-oauth2-strategy.js 
│ --- └── passport-local-strategy.js <br>
├── controller <br>
│ --- └──homeController.js
│ --- └──userController.js
├── mailers <br>
│ --- └──users_mailer.js
├── models <br>
│ --- └── User.js <br>
├── node_modules <br>
├── routes <br>
│ --- ├── index.js <br>
│ --- └── users.js <br>
├── views <br>
|      ├── mailer <br>
|            ├── password_reset.ejs <br>
│ --- ├── home.ejs <br>
│ --- ├── layout.ejs <br>
│ --- ├── reset_password.ejs <br>
│ --- ├── user_profile.ejs <br>
│ --- ├── user_sign_in.ejs <br>
│ --- ├── user_sign_up.ejs <br>
│ ---
├── .gitignore <br>
├── package.json <br>
├── package-lock.json <br>
├── README.md <br>
└── indedx.js <br>
