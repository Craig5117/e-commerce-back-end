# E-Commerce Back End
## Description 

An Express.js app that makes MySQL database calls that an e-commerce site could use to keep track of their stock and populate their pages for their customers to view their products.

---

## Table of Contents 

- [Built With](#built-with)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Acknowledgements](#acknowledgements)

---

## Built With

![JavaScript](https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![node.js](https://img.shields.io/badge/node.js%20-%2343853D.svg?&style=for-the-badge&logo=node.js&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?&style=for-the-badge&logo=mysql&logoColor=white)


---
## Installation

To install, first download or clone the repo, then run npm install to install the dependencies. Additionally, you will need to have MySQL installed for this to work.

[Back to Contents](#table-of-contents)

---

## Usage

[Video Tutorial](https://drive.google.com/file/d/1vy8KDAIjwk2L0hTcM7ziT8V00HN6t-0k/view?usp=sharing)

If you want to use locally, create a .env file in the root directory and add the following:

DB_NAME='ecommerce_db'

DB_USER='*Your MySQL Username*>'

DB_PW='*Your MySQL Password*'

Once the .env is set up, you will need to create the database. You can do that by opening a terminal in the root directory and starting MySQL. Then run source `db/schema.sql` in MySQL. Afterward, you can use the provided seeds in the seeds folder to seed your database. Feel free to rename the products, categories, and tags. Then run `npm run seed` to seed the database. You can also enter items one by one through the api endpoints.

Run `npm start` to start the server.

Products will be located at /api/products. Categories will be located at /api/categories. Tags will be located at /api/tags. Use the add the id for the product/category/tag to target a specific item to view, update, or delete.

Video tutorial also included in the link at the top of this section.

[Back to Contents](#table-of-contents)
  
---

## Contributors


---
---
    
Craig Bennett
    
[Craig5117](https://github.com/Craig5117)

---
---

[Back to Contents](#table-of-contents)

---

## Acknowledgements

- [Tech badges by Ileriayo](https://github.com/Ileriayo/markdown-badges)
- [Express.js](https://www.npmjs.com/package/express)
- [dotenv](https://www.npmjs.com/package/dotenv)


[Back to Contents](#table-of-contents)