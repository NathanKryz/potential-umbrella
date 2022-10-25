# potential-umbrella

## Description

The fellowing repository is a back-end project for an e-commerce themed database. Constructed primarily through JavaScript and using mySQL, it uses Object Relational
Mapping (ORM) to seed and allow usage of RESTful routes in order to GET, POST, PUT, or DELETE contents of tables within the database. This project was an excellent 
opportunity for me to practise proper API routing and all of the RESTful route practises, coupled with the exercise in using Objects for SQL calls. 

## Installation

In order to set up the development enviroment, first make sure to clone the repository to your local machine. From there you will want to make sure all modules required
are installed by running 'npm install' in the command line. From there, rename the .env.example file to just .env, and insert your mySQL credentials. From there, you
may either immediately proceed with development, or if you wish to have some data to work with, first log into your mySQL through 'mysql -u route -p' and enter your
password, then type in 'source ./db/schema.sql' to generate the database, and then exit mysql. From there, type 'node ./seeds/index.js' to seed the database, and then
all your parameters are set! As there is no web hosted side of the project, you will want to make sure you have a tool you can use to test routes, I used Insomnia 
myself.

## Usage

After the project has been installed proper, in the command line type 'npm start' to launch the application to Local Host at port 3001. Once launched, you can manipulate
the database using any program that allows for API calls towards any of the C.R.U.D. routes. There are three main tables, one accessed at /api/categories/ , another at
/api/tags , and a third at /api/products , all of which allow all 4 methods to be called.

[Video demonstration of the API calls](https://drive.google.com/file/d/1ycYTzMYRn9G7j-NntfT13A6i7KQXc7Yx/view)

## Credits

[Express.js](https://expressjs.com/)

[Sequelize](https://sequelize.org/)

[mySQL2](https://www.npmjs.com/package/mysql2)

[dotenv](https://www.npmjs.com/package/dotenv)

## License

This project is licensed by the MIT license: Do as you will, not my problem if you break it.
