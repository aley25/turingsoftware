#José Daniel Aley Challenge
# Turing Back End Challenge
To complete this challenge, you need to ensure all route returns a similar response object as described in our API guide.
To achieve this goal
- You will have to fix the existing bugs
- Implement the incomplete functions,
- Add test cases for the main functions of the system.
- Add Dockerfile to the root of the project to run the app in docker environment


## Getting started

### Prerequisites

In order to install and run this project locally, you would need to have the following installed on you local machine.

* [**Node JS**](https://nodejs.org/en/)
* [**Express**](https://expressjs.com/)
* [**MySQL**](https://www.mysql.com/downloads/)

### Installation

* Clone this repository

* Navigate to the project directory

* Run `npm install` or `yarn` to instal the projects dependencies
* create a `.env` file and copy the contents of the `.env.sample` file into it and supply the values for each variable

```sh
cp .env.sample .env
```
* Create a MySQL database and run the `sql` file in the database directory to migrate the database

```sh
mysql -u <dbuser> -D <databasename> -p < ./src/database/database.sql
```

* Run `npm run dev` to start the app in development

## Docker

* Build image

`docker build -t node_challenge .`

* Run container
`docker run --rm -p 8000:80 node_challenge`

## Request and Response Object API guide for all Endpoints
Check [here](https://docs.google.com/document/d/1J12z1vPo8S5VEmcHGNejjJBOcqmPrr6RSQNdL58qJyE/edit?usp=sharing)



i fix some bugs in the routes, and some problem to start the service, the babel was bad configured.
To start the app just start with the file called "start.js".
i didn´t finish anything because short time, i work on the project from 21/07/2019 4:30pm - 3:00am, and 22/07/2019 4:00pm- 10:00pm
Thanks for the test, i learn to much
