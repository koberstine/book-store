[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Book Wishlist

## Description

This project takes a fully functioning Google Books API search engine built with a RESTful API, and refactors it to be a GraphQL API built with Apollo Server. The application uses a typical MERN stack with React front end, MongoDB database, and Node.js/Express.js server. GraphQL is a relatively new tool gaining a lot of attention in web development as an alternative ideal for dynamic data updating and retrieval. The scope of this project is:

- Create an Apollo Server and apply it to an Express.js server as middleware.
- Modify the existing authentication middleware to work in the context of a GraphQL API.
- Create an Apollo Provider so that requests can communicate with an Apollo server.
- Build API endpoints with GraphQL in a MERN application.
- Use GraphQL queries and mutations to fetch and modify server-side data.
- Successfully configure and deploy a MERN application to Heroku.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Deployed-App](#deployed-app)
- [Screenshot](#screenshot)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation

Download source files, navigate in console to main project directory and run 'npm install' this will install the necessary packages in both the client and server applications.

## Usage

Navigate in console to main directory of project, run 'npm run start' to run the application on Local Host. The 'start' script in package.json will detect a development environment and use 'start:dev' or a production environment and use 'start:prod' there is also a 'heroku-postbuild' script for deployment to Heroku. Once deployed on Heroku, use the MONGODB_URI key to connect to MongoDB Atlas.

## Credits

Starter code provided by UCF Coding Boot Camp, University of Central Florida. Migration to GraphQL and Apollo Server accomplished by Chris Koberstine.

## Deployed-App

https://dashboard.heroku.com/apps/pure-gorge-10833

## Screenshot

![](https://github.com/koberstine/redux-store/blob/main/client/public/screenshot.jpg)

## License

[https://www.mit.edu/~amini/LICENSE.md](https://www.mit.edu/~amini/LICENSE.md)

    MIT License

    Copyright (c) [2021] [Chris Koberstine]

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

## Contributing

No contributions to this project are being accepted at this time

## Tests

No tests have been written for this project

## Questions

Github: [koberstine](https://github.com/koberstine/)

Please submit any additional questions via email to <koberstine@hotmail.com> with 'github.com/koberstine/book-wishlist' in the subject of the email.
