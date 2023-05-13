

# Ryan Park
 Hello! I am an undergrad at Northern Illinois University, I am
majoring in  computer science with an emphasis in Software
Development. Some of my  interests include video games, foreign cars,
and time outdoors. I am  currently located in the northwest suburbs of
Chicago. Feel free to contact me!

Reach me:
 - [LinkedIn](https://www.linkedin.com/in/ryanipark/)
 - [Twitter](https://www.twitter.com/ryanipark/)
 - [My website](https://ryanipark.com)
 - ryanpark@usa.com

## Current project - Recipe Web/Mobile Application
   **[Link to repository](https://github.com/ryanipark/recipe-web-app)**
   
   **Description:**  I'm in the process of making a recipe web application; it will allow for users to create/share/modify recipes. After the web application is stable, I will also develop a mobile application.

## Most recent completed project - Auto parts webstore
   
   **[Link to repository](https://github.com/467Group3A/rimjobs)**  
   **[~~Live site~~](https://rimjobs.store)**

**About the project:**   I am working in a team of four people to create an Auto Parts web store that uses technologies we have not been exposed to before. We have chosen the following tools in attempt to set some clear opportunities for learning. This website is based off a mechanic shop from a game called Saints Row.

**Project specifications:**  
- The store must utilize a read only legacy database and understand that the contents of it might change at any moment. (This DB holds the parts the site sells)
- We must build the website with the intentions of real world usage, meaning all aspects should be tested and innovated in a way that is optimal.
- We must build the website around our use case model [Model](https://i.imgur.com/x7YOp3N.png)
   
 **Tools:** 

 - Linux server to host the website
 - Node.js , express.js, and vue.js
 - MariaDB as a legacy database which holds a dynamic list of parts (This DB is read only)
 - SQLite3 as a local database which holds order information, shipping and handling charges, and employee information
 - The site implements a third party credit card authorization system which is viewed here [(CC auth)](https://blitz.cs.niu.edu/Monitor/#/credits) 
 - Python is used to dynamically pull and populate inventory from the legacy DB. 
 - [Pretty picture of our tech stack](https://i.imgur.com/3Za6oGh.png)

**My implementations:**  
*This technology is very new to me, so my focus has been all over the place as I attempt to learn as much as possible.*
 - Created an endpoint that allows for the 3rd party CC authorization to work
	 - Simple front end form in place to insure the response from the 3rd party auth is able to be displayed to the user
 - Created an interface that allows an employee to list all orders
	 - Allows to search by order status, total price range, and ID
 - Created an interface for employees that allows them to see each Order's information
	 - An employee is able to update an order status, once an order is filled they can print an invoice
 - Created a fulfillment interface for employees receiving inventory
	 - Employees are able to add to the sites inventory by part ID and amount
	 - They are also able to remove inventory from the site
 - Created an inventory endpoint that combines the part information from the legacy DB with inventory on hand from local DB.
      - This combined with our python scripts allows for parts from the legacy DB to be dynamically pulled.
 - Created and implmented a system that allows for shipping and handling charges to be inserted by an Administrator
      - This system only stores intervals in the DB, allowing for "weight brackets" by cost to be adjusted on the fly
 - Created a login system for employees and admins, their role decides which pages they can view
      - Restricts users not logged in from viewing pages
      - Uses express session variables
 - Created and implmented an email confirmation system for customers, it uses nodemailer to send an email to them.
 - Created a Manage logins page for Admins to add/delete employee/admin logins, it lists all users on the site.

## E-Commerce web store (2022)
[Repository: ](https://github.com/ryanipark/466-WebStore-Project)

**Description:** Worked in a team of five people to create a web store that interacts with a database. The website keeps track of a user’s personal information, orders, and product inventory. While it is relatively minimalistic, it is a fully functioning website that would allow users to browse, purchase, and receive products. It also includes and employee/owner control panel.

**Tools:** 

 - GitHub as a version control platform
 - MariaDB as a DBMS
 - PHP, CSS, SQL, HTML

**My focus:**  

 - Creating SQL scripts that clear or fill the database with info
 - Creating and optimizing safe SQL queries
 - Displaying products and their details to the consumer

**Small demonstration of the site:**


https://user-images.githubusercontent.com/98127886/190940081-08806c13-3579-4fab-89c3-829e7ecf1428.mp4



https://user-images.githubusercontent.com/98127886/190940114-4d4a6867-07d7-4882-afa8-d6af49b54bc3.mp4



https://user-images.githubusercontent.com/98127886/190940122-9c9440df-535a-4b5d-842f-372749b09359.mp4


## Repo index

 - Note: I had to private some repo's, if you're interested in seeing them, feel free to contact me!
 - [~~Intermediate Programming in C++~~](https://github.com/ryanipark/intermediateCPP)
 - [~~Data Structures and Algorithms~~](https://github.com/ryanipark/Data-Structures-Algorithms)
 - [~~Computer Programming in Assembler~~](https://github.com/ryanipark/Computer-Prog-Assembler)

