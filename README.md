## basic-redux-starter for development and production (with Heroku)
A simple Redux boilerplate with MongoDB, Express, Webpack + hot module replacement to build new projects faster.

#####To install use the following steps:

1. Download the zip file on the top of this github page or in terminal run:

    git clone https://github.com/chrisdziewa/basic-redux-starter/

2. In Config, rename the example-development.json:

    example-development.json -> development.json
3. Rename db in development.json to whichever db name you would like.
4. Update db name in db/index.js to use your db name (or change the log statement)

##### npm scripts

    npm run dev
* starts development server on port 3000
* Access website at http://localhost:3000/

    npm postinstall
* Builds your webpack production bundle automatically after being uploaded to Heroku

##### Bundle Locations

The main bundle is built at:

    /public/bundle.js

The /public/styles/style.scss file is compiled to:

    /public/main.css

##### React Development

The entry point to the React app is at:

    /public/src/index.js

and currently serves the App.js component from
    /public/src/containers/app.js


###### Hopefully this starter will be as useful to you as it is to me!
