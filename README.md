# Eden Frontend Task
This is a simple task that involves creating an employee management module using React. 


# Task Requirements
* Create two pages: one page to view the employee list and another to view a single employee's info
  
* CSS framework could be used such as Bootstrap, Material UI or any other framework.
  
* Styling should not completely depends on the framework but also you have to either add or overwrite the framework default styles.
  
* Pagination should be added and it is optional to add the funcutionality of switching between the pages.  
  
* Validtion must be apllied in edit and add of orders and all of the fields are required except address, which depends on the order    type, if it is "delivery" then required else not required.
  
* There are fields that can not be edited such as createdBy, createdAt, totalPrice and customerId.
  
* Optional pages could be added for the sake of creativity.
  
# Instructions
* Fork this repostiry to your personal account
* Clone The repository
* Run the server stub:
  - Install the dependencies
  ```bash
  npm i
  ```
  - Run the server
  ```bash
  npm start
  ```
* Create your react app in the same directory (https://www.npmjs.com/package/create-react-app)
* Complete the requirements
* Send us the link to your **public** repository after completing the task

# API Stub Documentation
The repository includes a script for a simple API stub (server.js). It contains four enpoints:
* GET /employees
  - Response Example
  ```JSON
  [
    {
      "name": "Michael Scott",
      "age": 45,
      "title": "Regional Manager",
      "id": 1
    },
    {
      "name": "Dwight Schrute",
      "age": 32,
      "title": "Assisstant to the Regional Manager",
      "id": 2
    }
  ]
  ```
* GET /employee/:id
  - Response Example
  ```JSON
  {
    "name": "Michael Scott",
    "age": 45,
    "title": "Regional Manager",
    "id": 1
  }
  ```
* POST /employees
  - Request Example
  ```JSON
  {
    "name": "Michael Scott",
    "age": 45,
    "title": "Regional Manager"
  }
  ```
  - Response Example
  ```JSON
  {
    "name": "Michael Scott",
    "age": 45,
    "title": "Regional Manager",
    "id": 3
  }
  ```




#### Notes: #### 
* Make sure to mention any assumptions you've made, extra features you've added in your email

