# EDEN-FrontEnd-Task
This repo contains a task for front-end developers to evaluate skills, knowledge and creativity.  

Mainly, the task needs to be done using React, however if you don't have previous experience with React framework you have 2 choices either to take the chance and accept the optional challenge to do the task with React or to do it using pure JavaScript, HTML and CSS.

# Order's Object
```Javascript
order: {
  customerId: String,
  customerName: String,
  customerPhoneNumber: String (Validation needed to be an Egyptain phone number specially in add and edit),
  orderList (order products array): [
    {
      productName: String,
      quantity: Number,
      price: Number
    }
  ]
  totalPrice (calculated from the orderList): Number,
  type (either onBoard or delivery): String,
  address: {
    appartmentNumber: Number,
    streetName: String,
    area: String,
    city: String
  }
  createdBy: String,
  createdAt: Date
}
```

# Task Requirments
  1- Create 2 main pages one to **add** the "order" and the other to **show, edit and delete**. 
  
  2- CSS framework could be used such as Bootstrap, Material UI or any other framework.
  
  3- Styling should not completely depends on the framework but also you have to either add or overwrite the framework default styles.
  
  4- Paggination should be added and it is optional to add the funcutionality of switching between the pages.  
  
  #### 5- Clean code is a must.
  
  6- Validtion must be apllied in edit and add of orders and all of the fields are required except address, which depends on the order    type, if it is "delivery" then required else not required.
  
  7- There are fields that can not be edited such as createdBy, createdAt, totalPrice and customerId.
  
  8- Optional pages could be added for the sake of creativity.

  9- Optional **Home page** could be added.


#### Notes: #### 
  1- For any assumptions or additional properties you want to add, please mention it in your readme file. 
  2- Fork this repo, do your task then submit the link.

