# E-commerce Back End Starter Code
# Description

 E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

Your challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

[![License: MIT](https://img.shields.io/badge/License-MIT-lightblue.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
- [User-Story](#user-story)
- [Acceptance-Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Author](#author)

## User-Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```


## Acceptance-Criteria

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

## Installation
To get the app running, first you must `npm i`, then run the `schema.sql` and go to seeds folder and run `index.js` to get the database started and populated.

After this you can fire up the server and go to insomnia to check different CRUD operations on the backend.




## Usage
### To start the application:
    npm run start
### or with nodemon:
    npm run watch
    
### API Endpoints
### All Products: 
        GET http://localhost:3001/
### Product by ID: 
        GET http://localhost:3001/:id
### Add Product: 
        POST http://localhost:3001/
### json
        {
            "product_name": "Sample",
            "price": 19.99,
            "stock": 100,
            "tagIds": [1, 2]
        }


## License


## Contributing



## Author
Github: VithusanU
