# JAVAFSD-Project04-master

## Table of Contents

- [General Info](#General-info)
- [Problem Statement](#Description)
- [Using the application](#Using-the-application)
- [Technologies](#Technologies)
- [Setup](#Setup)

## General Info

This is a Full Stack Developer - Frontend Project.

# Description

### Project objective:

As a Full Stack Developer, complete the features of the application by planning the development and pushing the source code to the GitHub repository.

Kitchen Story is an e-commerce portal that lets people shop  basic food items on their website. The website needs to have the following features:

    A search form in the home page to allow entry of the food items to be purchased by the customer.

    Based on item details entered, it will show available food items with  price.

    Once a person selects an item to purchase, they will be redirected to the list of available items. In the next page, they are shown the complete breakout of the order and details of the payment to be made in the payment gateway. When payment is done, they are shown a confirmation page with details of the order.

For the above features to work, there will be an admin backend with the following features:

    Admin login page where admin can change password after login if he wants to

    A master list of food items available for purchase

    A functionality to add or remove food items

You must use the following:

* VS Code: An IDE to code for the application

* Java: A programming language to develop the controller, databases, and others

* Git: To connect and push files from the local system to GitHub

* GitHub: To store the application code and track its versions

* Scrum: An efficient agile framework to deliver the product incrementally

* Search and Sort techniques: Data structures used for the project

* Specification document: Any open-source document or Google Docs


Following requirements should be met:

* The source code should be pushed to your GitHub repository. You need to document the steps and write the algorithms in it.

* The submission of your GitHub repository link is mandatory. In order to track your task, you need to share the link of the repository. You can add a section in your document.

* Document the step-by-step process starting from sprint planning to the product release.

* Application should not close, exit, or throw an exception if the user specifies an invalid input.

* You need to submit the final specification document which includes:

    * Project and developer details

    * Sprints planned and the tasks achieved in them

    * Algorithms and flowcharts of the application

    * Core concepts used in the project

    * Links to the GitHub repository to verify the project completion


## Using the application

These are the different controllers that are used to manage the data in backend.

<img alt = "Admin Controller" src = "https://github.com/Instantgaming2356/JAVAFSD-Project04/blob/master/Images/Screenshot%20(2609).png">

<img alt = "Customer Controller" src = "https://github.com/Instantgaming2356/JAVAFSD-Project04/blob/master/Images/Screenshot%20(2612).png">

1. User will have three choice to perform certain operations

    a. If User has selected "admin".

    b. If user has selected "customer".

    c. If user has selected "login-user".

2. In admin section, user can perform CRUD operation on products that are going to be available in stock and along with user can manage their details, email and password.

3. In Customer section, user has to enter its details for purchasing any products along with productId that is present in available stock.
  
4. In Login user section, as the user can manage the user details along with email and password. They can also purchase the available product directly through their userId and productId. 

5. The admin  can also view all the customers (including users) that have done any purchasing in this portal. And also list of users that are registered in this portal.


## Technologies

Technologies used in project:

-Typescript \
-HTML \
-CSS \
-BootStrap 3 

## Setup

Run this as a by using terminal in the project directory.

```
In terminal, >> ng serve
```
