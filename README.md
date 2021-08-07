# E-Commerce Back End

## Descrtiption

An e-commerce backend that allows a business owner to Create, Read, Update, and Delete information for their products. Products can have many Tags, but belong to only one category. This application follows RESTful API principles and can CRUD entries to the MySQL database. Built using Express &amp; Sequelize to interact with a MySQL database.

## Insallation

* Create the database schema by running the following from the MySQL shell:
    - source schema.sql;
* Seed the database by running the following from the command line:
    - npm run seed
* Start the server by running the following from the command line:
    - npm start

## Finished Product

A video demonstration of this application's capabilities can by viewed at the link below:
* [Video Demonstration](https://drive.google.com/file/d/1UpKpWESom8VHJnDTMfwqa4oEFHd5a-X0/view)

## Technologies Used

Built in Visual Studion with:
* Node.js
* MySQL
* Express.js
* Sequelize.js
* npm

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Contact Me

Questions, comments, or concerns about this project? Check out my Github or contact me via e-mail.

* GitHub: [spreston4](https://github.com/spreston4)

* E-mail: [sam.preston11@gmail.com](mailto:sam.preston11@gmail.com)
