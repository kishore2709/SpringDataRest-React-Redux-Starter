# SpringDataRest-React-Redux-Starter (This project was a spike and is stopped)

Bootstrap to start a project with [Spring Data Rest](http://projects.spring.io/spring-data-rest/) and [React.js](https://facebook.github.io/react/) + [Redux](http://redux.js.org/)

The project:

- Contains a demo app that can be removed easily.

## Setup:

You just need [Maven](https://maven.apache.org/). It will generate all compiled java classes, install node and npm locally and also install node dependencies for you. Everything will be stored in _target_ folder.


  - If you have maven installed locally

    - Run `mvn clean compile` to generate all required source files
  
  - If don't, but you use IntelliJ as IDE

    - Open _maven tool window_ an run **compile** command in the _lifecycle_ folder

## Frontend

  - If you have not installed node and npm locally:
  
    - Go to _src/main/frontend_ where is package.json
    - Run:
      - `../../../target/node/npm start` to launch a local server with _livereload_ 
      - `../../../target/node/npm run build` to build the minified bundle 
      - `../../../target/node/npm run test:watch` to run and watch the tests 

  - If node and npm locally:
  
    - Go to _src/main/frontend_ where is package.json
    - Run:
      - `npm start` to launch a local server with _livereload_ 
      - `npm run build` to build the minified bundle 
      - `npm run test:watch` to run and watch the tests 

## Troubleshooting

  - If you make changes in the frontend and you want to see te entire app (backend <-> frontend) working correctly, you must have to run `npm run build` and then _run_ your java project to see the front changes.
  
## TODO:

  - Authentication with OAuth
  - Styles
  - Frontend Tests
