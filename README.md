  # E-Commerce Backend
 
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
 
  ## Table of Contents
  
  [Description](#description)

  [Installation](#installation)
  
  [Usage](#usage)

  [Contribute](#contribute)

  [Test](#test)
  
  [Credits](#credits)
  
  [License](#license)

  [Questions](#questions)
  
  ## Description
  This is the backend of a hypothetical E-Commerce service that manages the database of all products for sale.

  ## Installation
  This requires ExpressJS, MySql, Sequelize,MySQL2, and dotenv.

  ## Usage
  Users can fire up the server by entering 'node server.js' in the command line while in the root folder of the application. Because this is simply the backend, all other activity for engaging with it is done through Insomnia or some other API development platform. Once the server is live at localhost:3001, users can navigate to  'localhost:3001/api' and then enter one of three other query parameters: '/products', '/categories', '/tags'. Users can perform get requests on any of these queries in Insomnia. Doing so would yield all of the appropriate data (including relational data) for that query. Users can also perform POST requests to add new items to each table in JSON notation (which means object keys must exist within double quotes).In addition, users can also search for a single line item in each table, by adding '/:id' (where ':id' is the id number for the desired category, product, or tag) to the url. With this query, users can not only perform GET requests on a single line item, but also PUT requests to update that single item, or delete requests to remove that item from the database. 

  ![alt text](./screencap1.PNG)
  ![alt text](./screencap2.PNG)
  
  ## Contribute
  [GitHub Repo: (https://github.com/https://github.com/AdamJohnson92/E-Commerce-Back-End)]

  
  ## Credits
  Starting code courtesy of Bootcamp Spot, and assistance with clearing up a bug that stopped the 'include: Products' statement to work properly on Tag GET requests courtesy of BCS Substitute Instructor Nathan Shown.

  ## License
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
  This project utilizes ExpressJS, MySQL2, and Sequelize, which are licensed under the terms of the MIT license.

  ## Questions?

  Contact me at:

  GitHub: https://github.com/AdamJohnson92
  
  email: adamgjohnson92@gmail.com