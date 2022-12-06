# Codealong Knex.js Table Migrations

For full instructions please see the codealong in Synapse!

## Setup

- Create a new database, for example a new db called `instock`
- Edit `.env` with your MySQL credentials and db name
- Install node_modules `npm install` in the root folder, where the `package.json` file is
- Create tables by either running `knex migrate:latest` if you have the Knex CLI installed, or run `npm run migrate` from the package.json scripts
- After creating tables run either `knex seed:run` or `npm run seed` to populate the tables with data
- Finally you can start the project by running either `npm start` or `npm run dev`, the 2nd option will start with `nodemon`

# Procedure

Look at .env
.env used in knexfile.js

Make database locally
install packages
    run npm i
run migrations
    npm run migrate
run seeds
    npm run seed

Spin up server
    npm run dev

Push to Github

Set up React app and test

TODO:

revise .env variables to correspond to deployment
deploy server-side to heroku

deploy client-side to netlify