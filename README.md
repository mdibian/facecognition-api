# Facecognition API

This project contains the back-end server code for the [Facecognition](https://facecognition.herokuapp.com/) application, whose files can be found here in [facecognition](https://github.com/mdibian/facecognition) repository. The project is pretty simple and was intended only to put some web development technologies into practice.

## Technologies

The project back-end was made with:

1. [Node.js](https://nodejs.org/en/)
2. [Express.js](https://expressjs.com/)
3. [PostgreSQL](https://www.postgresql.org/)

## Run the project locally

To get the back-end server properly working for the project, you'll need to download, install and configure an user and password for Postgres. You can use the database dumped file named **dbschema.sql** which was provided in this repository in order to recreate the database schema.

Once the step above is done, fill the blanks on the **credentials** file with your user and password for the database, as well the database name. In the same file you'll see an API key, this is a free tier one so I left It for you for more convenience.

After this, run the command below to install all dependencies
 ```
 npm install
 ``` 
 
Then, you can initate the project by running
 ```
 npm start
 ```

You should run the development server before running the front-end application, this way the port won't be already being used.
