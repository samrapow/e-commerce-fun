# Homework 13 - E-Commerce Back-end

## Description

I created an e-commerce back-end application. I configured a working Express.js API to use Sequelize to interact with a MySQL database.

```md
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

## Demos

Create schema, seed databse, and start application server
![Walkthrough video of creating schema, seeding the database, and starting the application's server](/Assets/homework-13-start-demo.gif "Walkthrough video of creating schema, seeding the database, and starting the application's server")

[Link to Demo#1](https://watch.screencastify.com/v/0gNojzxQqpnJVnQLpptD)

Test get, get by id, post, put, and delete routes for category-routes.js
![Walkthrough video of testing routes for category-routes.js](/Assets/homework-13-category-routes.gif "Walkthrough video of testing routes for category-routes.js")

[Link to Demo#2](https://watch.screencastify.com/v/dQfFvYPqykHmhHEGcnZ4)

Test get, get by id, post, put, and delete routes for product-routes.js
![Walkthrough video of testing routes for product-routes.js](/Assets/homework-13-product-routs.gif "Walkthrough video of testing routes for product-routes.js")

[Link to Demo#3](https://watch.screencastify.com/v/9ujMI5bIeuj4cOkMFmqj)

Test get, get by id, post, put, and delete routes for tag-routes.js
![Walkthrough video of testing routes for tag-routes.js](/Assets/homework-13-tag-routes.gif "Walkthrough video of testing routes for tag-routes.js")

[Link to Demo#4](https://watch.screencastify.com/v/m1kuToAsLzX5TzKv3M6M)


## GitHub Repository

[Github Repository](https://github.com/samrapow/homework10-team-profile-generator)