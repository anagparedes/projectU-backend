# ProjectU

By [Ana Paredes](https://github.com/anagparedes)

Web application with MERN Stack (MongoDB, Express, React, and Node.js) for Technical Test workshop in [Solvex Dominicana](https://solvex.com.do/). The goal was to build a project management site where users can create new projects, add tasks, and update their progress as they work.

## How to Start

Download or clone this repository. Then in main ProjectU-backend folder use:

```js
npm install
```

In order to get the MongoDB working, create a ".env" file in your project folder. Create variables in the .env file called MONGO_URL and SESSION_SECRET and set it equal to your Mongo connection string and secret phrase respectively. To run this program open up terminal to the main folder and another terminal window with the frontend folder.

In backend use:

```js
npm test
```

In frontend use:

```js
npm start
```

## Folders

- auth: contains Passport.js set up/config files
- db: contains a js file that connects the functionality established in the routes to respective collections in MongoDB
- frontend: contains all frontend material
  - public: houses index.js
  - src: contains javascript files and corresponding stylesheets used to build the site pages (organized by page/component)
- routes: contains the js files that run the express routing
