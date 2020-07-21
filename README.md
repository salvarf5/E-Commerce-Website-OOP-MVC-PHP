# E-Commerce-Website-OOP-MVC-PHP
E-Commerce Website OOP MVC PHP

# How it works
* The system is built 100% in PHP(some HTML, Javascript and JQuery knowledge is required). Created my own MVC from scratch
* CSS used for the UI.

# Description
The designed application has been created with my own MVC from the scratch and has an admin view and the public or guest view. The admin view is meant for the administrator to manage the products, edit, remove and add products, manages categories, changes the status of an order, and manages customer notifications. The customer view will be accessible to the customers, and they will be able to order for products from the shop.
The application has a registration form to register new users, and a password recovery option for an existing user.
Any user can browse products, add, and replace or delete a product from the cart, but only users with an account created will be able to make the purchase. All the products added to the cart before login will be transfer to the customer cart once he/she has logged in.

**Customer view**<br><br>
Shopping cart: the customer has the ability to have the products added to his cart saved even after the costumer logout, and place the order at any time
If for any reason one the products in the cart is not available at the time of the purchase, the application will inform the customer about it and will save the product in his cart. The customer will have the possibility of creating an alert to inform him once the product is back in stock.<br>
![readme1](https://user-images.githubusercontent.com/54718360/87975922-8e6f0100-cacc-11ea-873e-43cdf65eaa8c.png)<br>
Also, the application will not allow adding more units of a product than available in stock<br>
![readme2](https://user-images.githubusercontent.com/54718360/87976219-05a49500-cacd-11ea-971d-8e8e5924d994.png)<br>
Orders: the customer has the option of checking all the orders he/she has made as well as the status and the details of any order in particular.<br><br>
**Admin view**<br><br>
Manage categories: this unit will allow the admin to add a new product category.<br>
Manage products: as mentioned before, this will allow the admin to add, edit or delete a product.<br>
Manage orders: this option will allow the admin to change the status of an order.<br>
Client notifications: this unit was created to store all the alerts that have been created by customers. The application will show a notification alert when a customer creates a new alert as shown below<br>
![readme3](https://user-images.githubusercontent.com/54718360/87976398-587e4c80-cacd-11ea-998d-8d37d261be00.png)<br>
Whichever alert is new will be shown in the table with the label “new”. <br>
![readme4](https://user-images.githubusercontent.com/54718360/87976571-9e3b1500-cacd-11ea-8339-38f1e44d215b.png) <br>
If you mark the alert as seen this will remove the notification alert ![readme7](https://user-images.githubusercontent.com/54718360/87977308-d4c55f80-cace-11ea-926a-1c672910f4f5.png)<br>
If the product is back in stock the application will pop-up an alert message once the admin has logged in to make sure no customer notification is missed.<br>
![readme5](https://user-images.githubusercontent.com/54718360/87976653-c9bdff80-cacd-11ea-89d6-71d6dd75c784.png)<br>
The admin has the option to send an email by clicking the email icon once the product is back in stock. The application will fetch the user email from the database and generate an automatic email that will be sending to the customer with the product information. If you click on the product you will be redirected to the website.<br>
![readme6](https://user-images.githubusercontent.com/54718360/87976722-de01fc80-cacd-11ea-82e7-3000519b3820.png)






# Requirements
* PHP.
* Web Server (I personally use XAMPP).
* MySQL.
* HTML
* CSS.
* Javascript/JQuery.

# How to use it
* Simply download the source file to your computer.
* Import the file store.sql into the current DBMS.
* Change database password and username if nedeed in the db.php file.
* Change base_url if nedeed in the parameters.php file.
* Save the files, upload them to your webserver and give it try.

# Author
Salvador Rodriguez (whole project).
