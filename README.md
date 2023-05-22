# User Management System

This repository contains the implementation of a User Management System, which includes microservices to fetch user data from an API, store the data in a database, publish the user data to the frontend, update the data in the database, export the data into a CSV file, and a frontend application to view and update the user data.

Assumptions :-
You have a Gmail ID to login and obtain the API Token from https://gorest.co.in/.
The User Master table already exists in the database.
The database credentials are properly configured in the microservices.
The microservices are written in a language/framework of your choice (e.g., Node.js with Express, Python with Flask, etc.).
The frontend application is developed using a suitable framework (e.g., React, Angular, Vue.js, etc.).
The database used is compatible with the chosen microservice language/framework.
The CSV export script is implemented as a separate microservice.
The API access screenshots and Postman collection file are provided.
Installation and Setup/

Clone the repository to your local machine:
git clone https://github.com/your-username/user-management-system.git

Navigate to the project directory:
cd user-management-system

Install the dependencies for each microservice by following the instructions in their respective directories:
api-fetcher: Instructions to install dependencies can be found in the api-fetcher directory.
data-store: Instructions to install dependencies can be found in the data-store directory.
frontend: Instructions to install dependencies can be found in the frontend directory.
csv-exporter: Instructions to install dependencies can be found in the csv-exporter directory.
Set up the database by executing the provided DB script in your chosen database management system.

Configure the microservices with the necessary environment variables:
api-fetcher: Set the API Token and database connection details as environment variables. Refer to the config.example.env file in the api-fetcher directory.
data-store: Set the database connection details as environment variables. Refer to the config.example.env file in the data-store directory.
csv-exporter: Set the database connection details as environment variables. Refer to the config.example.env file in the csv-exporter directory.

Start each microservice:
api-fetcher: Follow the instructions in the api-fetcher directory to start the microservice.
data-store: Follow the instructions in the data-store directory to start the microservice.
frontend: Follow the instructions in the frontend directory to start the microservice.
csv-exporter: Follow the instructions in the csv-exporter directory to start the microservice.

Usage:- 

Once the microservices are up and running, open a web browser and navigate to the frontend application.
In the frontend application, you should be able to view the user data fetched from the API.
Edit the user data as required and save the changes.
The updated data will be sent
