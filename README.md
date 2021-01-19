# ReactFullStack
a sample stateful and server-side rendered React application

Create a Development Environment for Node and React

1. Initializing

$ mkdir ReactFullStack
$ cd ReactFullStack
$ npm init


2. Install Main Dependencies

$ npm i express
$ npm i react react-dom
$ npm i webpack webpack-cli
$ npm i babel-loader @babel/core @babel/node @babel/preset-env @babel/preset-react


3. Install Development Dependencies

$ npm i -D nodemon
$ npm i -D eslint babel-eslint eslint-plugin-react eslint-plugin-react-hooks
create .eslintrc.js file as in the project
$ npm i -D jest babel-jest react-test-renderer


4. Create an Initial Directory Structure

ReactFullStack/
  dist/
    main.js
  src/
    index.js
    components/
      App.js
    server/
      server.js
      
5. Configure Webpack and Babel

create babel.config.js file as in the project
create web.config.js file as in the project

6. Create npm Scripts for Development

"dev:server": "nodemon --exec babel-node src/server/server.js --ignore dist/"
"dev:bundler": "webpack -w --mode=development"


7. Testing Everything

use App.js, index.js and server.js files
run both npm dev:server and dev:bundler scripts in 2 separate terminals
$ npm run dev:server
$ npm run dev:bundler


