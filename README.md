# Instock-backend

-   Initial folder setup
-   Install express, nodemon, mysql2, cors, dotenv, knex, and uuid (just incase)
-   Create .env and .env.sample
-   Create .gitignore
-   Create basic controller and route files

## Develop Branch

## Migrations and Seeds

### Installation

-   Create a .env file locally and add values for the following variables.

```bash
  PORT=8080
  DB_HOST=127.0.0.1
  DB_NAME=instock
  DB_USER=
  DB_PASSWORD=
```

-   Create a database locally called instock
-   Run the following commands

```bash
npm run migrate
```

```bash
npm run seed
```

### Feature/ GET single item details

-   define inventory page routes
-   link page routes to inventory controller
-   define GET request for details of a single item
-   awaiting database for testing
-   tested and working

### Feature/ GET all warehouses

-   Create route for GET-warehouse-list
-   Create controller function to send the list of warehouses
-   Tested API with Postman, working on my end
-   Define inventory page routes
-   Link page routes to inventory controller
-   Define GET request for details of a single item
-   Awaiting database for testing (resolved)
-   Migrate database tables
-   Tested and working
-   Seed database tables

### Feature/ POST new inventory item

-   Create controller function
-   Chose the cascading style of 'if/else if' checks for validation so that reponses could be specific
-   Awaiting 'GET warehouse-list' API to be completed so that the warehouse # can be checked
