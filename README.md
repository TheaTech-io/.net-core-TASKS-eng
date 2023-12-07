# This repo is for .net core candidate selection. 

Procedure

Please open a github repo for this task and share its address with us. The task is expected to be completed with .NET CORE. There are no product/technology limitations such as 3rd party tools such as database, queue, etc. for the tasks. You can use any external resources except artificial intelligence. Please specify the external resources and codes you use as a comment in the task. You have a time limit of 3 days after the task is delivered to you. You have to use a software architecture. However, you are free to use any architecture you wish. Your commits are valuable for us to check the progress. You do not have to complete the project completely. You can also submit as much as you progress. Our goal here is your approach to clean code.

Docker

The task development should be able to be deployed and tested on the Docker platform.

1: Auth System - JWT Bearer Token The user must be able to log in with a valid username and password.

The user should receive an error when entering an invalid username or password when logging in.

The user should be able to make other API requests using the JWT Bearer Token received after login.

The user should receive an authorization error when attempting to make an API request without using a valid JWT Bearer Token.

The user should be automatically logged out if the JWT Bearer Token has expired.

2: Swagger Documentation
1-The user should see the Swagger UI interface when accessing the application.

2 -The user should be able to view all API endpoints and parameters in the Swagger UI interface.

3 -The user should be able to try any API request from the Swagger UI interface and see the results.

4 -The user should see the appropriate error message in case of any error in the Swagger UI interface.

3: Products and Cart The user should be able to add products and fill in the required fields correctly.

User should be able to list products.

User should be able to add products to their cart.

The user should receive an error if the product they are trying to add to their cart is out of stock.

4: Discounts API

When you want to access your cart, you should be able to calculate the discount in the cart.

when the total amount of the cart is 1000 TL or more, the system should verify that a 10% discount is applied.

The system must verify that one of products is given free of charge when 6 products from a category with 2 IDs are purchased.

The system should verify that a 20% discount is applied to the cheapest item when two or more items from a category with 1 ID are purchased. 

The system should be able to make correct discount calculations considering any new discount rules that may be added in the future.
