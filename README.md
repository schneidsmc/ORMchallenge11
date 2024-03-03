<h1 align="center">ORM Challenge </h1>

<div style= "text-align: center">

  <img src="https://img.shields.io/github/repo-size/schneidsmc/ORMchallenge11" />
  <img src="https://img.shields.io/github/languages/top/schneidsmc/ORMchallenge11" />
  <img src="https://img.shields.io/github/last-commit/schneidsmc/ORMchallenge11" />
<br />

  <img src="https://img.shields.io/badge/Javascript-yellow" />
  <img src="https://img.shields.io/badge/jQuery-Express"  />
  <img src="https://img.shields.io/badge/-node.js-green" />
  <img src="https://img.shields.io/badge/-inquirer-red" >
  <img src="https://img.shields.io/badge/-dotenv-lightgrey" />
  <img src="https://img.shields.io/badge/-mySQL2-pink" />
</div>

## Description 📚

- What was your motivation? Why did you build this project? What problem does it solve? What did you learn?

This project builds the back end for an e-commerce site. It takes a working Express.js API and configures it to sequelize that interacts with a MYSQL database.

This was created using Markdown,Javascript,NodeJS.

## Table of Contents

- [User-Story](#user-story)
- [Acceptance-Criteria](#acceptance-criteria)
- [Installation](#installation-📋)
- [Usage](#usage-🏁)
- [Demonstration](#demonstration)
- [Author](#author-👋🏽)

## User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria

GIVEN a functional Express.js API:

- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia Core for categories, products, or tags THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia Core THEN I am able to successfully create, update, and delete data in my database

## Installation 📋

- What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.

`git clone https://github.com/schneidsmc/ORMchallenge11.git`

Once you have cloned the repository to your local machine and created your own repository on git hub, you can push it to your own github repository using `git remote set-url origin <REPO LINK>`

## Usage 🏁

The usage of this assignment is through insomnia. Run `npm install`, `node seeds/index.js` and `npm start` and the console log will say 'Now Listening'. Then you can test the GET POST and DELETE routes in insomia using localhost:3001.

## Demonstration

LINK SYNTAX
[here]()

IMAGE SYNTAX
<img src="" alt="description" width="300" height="auto">

## Author 👋🏽

GitHub Username: [schneidsmc](https://github.com/schneidsmc)

📧 Email: schneidsmc@gmail.com

This README was created with ❤️ using README Generator 👏🏽👏🏽
