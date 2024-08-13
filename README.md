# PWA - J.A.T.E (Just Another Text Editor)

## Table of Contents

- [PWA - J.A.T.E (Just Another Text Editor)](#pwa---jate-just-another-text-editor)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Technologies and Packages Used](#technologies-and-packages-used)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Application Deployed on Render](#application-deployed-on-render)
    - [Screenshots of the Application](#screenshots-of-the-application)
  - [Credits](#credits)
  - [License](#license)

## Description

This a progressive web application, "PWA" in the form of a text editor. The application uses [Express.js](https://expressjs.com/) for handling the routes and server as well as several packages for building and managing the PWA such as [Babel](), [Webpack](),  The [Node language manager](https://expressjs.com/) uses those packages to perform CRUD actions such as to create, update, get, and delete the users, their "thoughts', reactions to thoughts, and managing friends of users. To easily interact with these API calls a user can use an application such as [Insomnia](https://insomnia.rest/).

Creating this application taught me a new way to manage the database without a set relational structure. There was intensive learning of the new ways to setup managing a database in MongoDB and using Mongoose. Further development involves implementing a front end for a nicer appearance and direct user interaction with the app.

## Technologies and Packages Used

- [Node.js](https://nodejs.org/en)
- [Express.js](https://expressjs.com/)
- [Babel]()
- [Concurrently]()
- [Webpack]()
- [Workbox]()
- [Cache]()
  
## Installation

This is a full functioning

First to use this application head to [PWA - J.A.T.E](https://github.com/EXCervantes/pwa-jate) and clone the repository. To learn how to clone a repository checkout this guide [Cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).

You must have `Node` installed on your system. Go [here](https://nodejs.org/en/learn/getting-started/how-to-install-nodejs) for instructions on how to do so. To properly run this application you must have [MongoDB](https://www.mongodb.com/) installed on your system. Run `npm i` in the root directory to install the necessary dependencies onto your system.

## Usage

Once Node, MongoDB, and the necessary dependencies have been installed, initialize the application in the Terminal in VSCode and run `npm run dev` or `npm run start`. Now the server is active and a user can use an application such as [Insomnia](https://insomnia.rest/) to perform the CRUD operations with this application.

There are full CRUD operations for "users" and "thoughts" also known as posts, and both create and delete methods for "reactions", or comments to thoughts and a user's friends. Also note deleting a user will also remove that particular user's thoughts from the database.

### Application Deployed on Render

Follow [this link](https://pwa-jate-zgyl.onrender.com/) to visit this application's page and install it locally.

### Screenshots of the Application

![Users](images/socialnetworkapiscreen1.jpg)
![Thoughts](images/socialnetworkapiscreen2.jpg)
![Reactions](images/socialnetworkapiscreen3.jpg)
![Friends](images/socialnetworkapiscreen4.jpg)

## Credits

Referenced for how to cascade delete the user's thoughts from the database in MongoDB.

"_node.js - MongoDB Delete all documents that created by user when deleting user - Stack Overflow_". (2018, June 12). Stack Overflow. Retrieved August 3, 2024, from https://stackoverflow.com/questions/50814052/mongodb-delete-all-documents-that-created-by-user-when-deleting-user
  
## License

This project is licensed under [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Please see the [License](https://opensource.org/licenses/MIT) page for more info.

