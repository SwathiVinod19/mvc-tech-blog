# mvc-tech-blog
A site where developers can publish their blog posts and comment on other developers’ posts. It is made using Handlebars, Sequelize, express-session npm package

## Description

Writing about tech can be just as important as making it. Developers spend plenty of time creating new applications and debugging existing codebases, but most developers also spend at least some of their time reading and writing about technical concepts, recent advancements, and new technologies. A simple Google search for any concept covered in this course returns thousands of think pieces and tutorials from developers of all skill levels!
This is a blog site where developers can publish their posts and comment on other developers’ posts. It is made using Handlebars, Sequelize, express-session npm packages

## Table of Contents
---
* [License](#License)
* [Installation](#Installation)
* [Usage](#Usage)
* [Screenshots](#Screenshots)
* [Contributing](#Contributing)
* [Questions](#Questions)
  
---


## License

[MIT License](https://opensource.org/licenses/MIT)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Installation
1. Check if you have Node.js installed in your computer by typing `node -v` in your command line.
2. If node is not installed, visit the [Node.js](https://nodejs.org/en) website to install. 
3. Clone this project repository to your computer. 
4. Use the command `npm i` or `npm install` to install all dependencies. 

## Usage

* Create a file in the root directory titled `.env` and include database name and personal MySQL login information:
```
DB_NAME='YOUR DATABASE NAME'
DB_USER='YOUR USERNAME'
DB_PW='YOUR PASSWORD'
DB_SESSION_SECRET='YOUR SECRET PASSWORD FOR THE SESSION'
```
* Open MySQL with command `mysql -u root -p` and enter your personal MySQL password. 
* Create databse with command `source schema.sql`. Log out of MySQL with command `\q`.
* Seed database with command `npm run seed`.
* Start the server with either `npm start` or `node server.js`

