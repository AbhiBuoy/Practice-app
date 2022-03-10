# Practice React JS Project

## The purpose of the proect is

This Project is a Simple ReactJS Project which demonstrates the following
1. How to create a component in react
2. How to make http calls
3. How to communicate between parent and child component.
4. How to use bootstrap library with react
5. How to use basic routing in react

The project Template can be used to build bigger projects



## Prerequisites

### Install Node JS
Refer to https://nodejs.org/en/ to install nodejs

### Install create-react-app
Install Practice_app npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install create-react-app

```bash
npm install -g Practice_app
```

## Cloning and Running the Application in local

Clone the project into local

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```bash
npm install
```

In order to run the application Type the following command

```bash
npm start
```

The Application Runs on **localhost:3000**

## Application design and plan

#### Components

1. **Customers** Component : This particular component displays all the  list of customers. This Component gets the data from a json file in assets folder.

2. **CustomerDetails** Component : This Component Displays the details of the particular selected customer. This Component gets its data from a json file in assets folder as well. This Component is the Child Component of *Customers* Component

#### HTTP client

**axios** library is used to make HTTP Calls



