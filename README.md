
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/license/mit/)

  # E-Commerce Backend

  ## Description

    This is a backend application for an e-commerce site. It uses Express.js API and Sequelize to interact with a MySQL database. The database includes tables for products, categories, tags, and product tags. The application creates the database using mySQL with models and associations. It also has API routes to perform RESTful CRUD operations using sequelize models to interact with the database. The application is invoked by using the command line and entering node server.js. The user can then use Postman or Insomnia to test the routes.
  


  ## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contribution)
- [Tests](#tests)



## Installation

Clone the repository, then run `npm install` to install the dependencies. 

use mysql to create the database by running `mysql -u root -p` and entering your password. Then, run `source db/schema.sql` to create the database.

Then, run `npm run seed` to seed the database. Finally, run `npm start` to start the server.




## Usage 

[![Video Demonstration](https://drive.google.com/file/d/1ghgeRFQeY_JiR8Kkte2fG4D63XjSBgBa/view)](https://drive.google.com/file/d/1ghgeRFQeY_JiR8Kkte2fG4D63XjSBgBa/view)




Video demonstration: https://drive.google.com/file/d/1ghgeRFQeY_JiR8Kkte2fG4D63XjSBgBa/view

After installing the dependencies, seeding the database, and starting the server, the user can use Postman or Insomnia to test the routes. The user can test the GET routes to return all categories, all products, and all tags. The user can also test the GET routes to return a single category, a single product, and a single tag. The user can test the POST routes to create a new category, a new product, and a new tag. The user can test the PUT routes to update a category, a product, and a tag. Finally, the user can test the DELETE routes to delete a category, a product, and a tag.

## License

please see license in repository


## Tests

you can test this application by using Postman or Insomnia to test the routes.

