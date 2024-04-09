# 14-MVC-Tech-Blog

## Table of Contents-
- [Tech Blog using MVC Format](#mvc-tech-blog)
  - [Table of Contents-](#table-of-contents-)
  - [Licensing](#licensing)
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Credits](#credits)
  - [Contributing](#contributing)
  - [Testing](#testing)
  - [Additional Info](#additional-info)

## Licensing

[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)

Link: [MIT License](https://opensource.org/licenses/MIT)

## Description

A simple "Tech Blog" website using the Model-View-Controller format. A MySQL database is used to store User data, as well as Posts and Comments on those Posts. Database modelling is done through the Sequelize ORM for MySQL. The API ("Controller") functions are accessed using Express.js web application framework. The "View" functions are provided by Handlebars.js templating system.

## Installation

Can also be installed locally by copying directory structure as-is, then doing a `npm install` in the base directory to install necessary dependancies. Application database is MySql, and the database container can be created by navigating to the `/db` directory and then using the MySQL command line utility and the `SOURCE` command to create it. Data tables can be seeded into the container after this by navigating to the `/seeds` directory and using the command `node seed.js` to create them.

## Usage

To run when installed locally: The app server is launched by Node, type the command 'node server.js' to start the back-end. Then launch a web browser and go to the URL 'localhost:3001/' to get the inital page.

## Credits

This application uses the following technologies/libraries:  

[Express.js](https://expressjs.com/)

[Sequelize](https://sequelize.org/)

[MySQL](https://www.mysql.com/)

[dotenv](https://www.npmjs.com/package/dotenv)

## Contributing

  I am not accepting any contributions at this time.

## Testing

  No testing is provided.

## Additional Info

- Github: [John Lott](https://github.com/johnlott1)
- Email:lott.john99@gmail.com