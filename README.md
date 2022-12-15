<h1 align="center">Object-Relational Mapping (ORM): E-Commerce Back End </h1>
   
## Description

A mysql database and application backend for an e-commerce site. Built using MySQL2, Express, Sequelize and dotenv.
  
Below are the gifs showing the functionality of the application:
  
![DB Setup and Server Start](./assets/DB%20Setup%20%26%20Server%20Start.gif)

![GET All Categories, Products, & Tags](./assets/GET%20All%20Categories%2C%20Products%2C%20%26%20Tags.gif)

![GET All Categories, Products, & Tags by ID](./assets/GET%20by%20ID.gif)

![POST PUT DEL Categories](./assets/POST%20PUT%20DEL%20Categories.gif)

![POST PUT DEL Products](./assets/POST%20PUT%20DEL%20Products.gif)

![POST PUT DEL Tags](./assets/POST%20PUT%20DEL%20Tags.gif)
  
The full movie files showing the functionality of the application can be found in the assets directory
  
## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
``` 
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
  
## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Installation
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Usage  
  
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter your MySQL2 PW when promted

`source db/schema.sql`

`exit`

`npm run seed`
  
`npm start`


## Contributing
[Matthew Lahey](https://github.com/mdlahey1)