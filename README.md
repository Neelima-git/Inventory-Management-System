# Inventory-Management-System
This repository contains all the back-end code used for developing Inventory Management System which is assigned as a part of AI/ML Skill India scholarship. 

### About the repository
The project is implemented using Python, NoSQL database(JSON) and File Handling.

### Files 
1. Add products: This file contains code for adding or updating products in the repository.
2. Purchasing: This file contains code for nuying products form inventory.
3. Products.json: This file has details of all the products in the inventory.
4. Sales.jsonL This file has transaction history of all the purchases.

### Features for adding products to inventory
1. Add new items into inventory if the product doesn't already exist in Inventory.
2. Update the number of units available for a product if the product already exists in inventory.
3. Products have 7 attributs that include product_id, product_name, MRP, Net Weight, Number of units available, Manufacture date and Expire date. 

### Features for purchasing products by the user
1. Check for the user enquired product in the inventory.
    1. If product exists proceed further.
    2. If no, inform user that the product isn't available in inventory.
2. Enquire number of units/quantity for the product that the user want to buy.
    1. If that many units are available proceed further.
    2. If no, then inform user about the number of units available for purchase in the inventory.
3. Display the product name, unit price and bill amount for the user.
4. Ask for the payment method cash/card. 
5. If selected card, then ask for PIN number and details.
6. After the successful transaction, all the transactional details like transaction_id, product_id, product_name, number of units purchased, total bill amount, date and time of transaction are all updated in the NoSQL database. 

### About me
Hey there! I'm Neelima Bellana, a final year undergrad majoring in Computer Science. I'm a web developer and a ML enthusiast. 
You can connect with me here👇
<p align="left">
<a href="https://linkedin.com/in/neelima-bellana" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="neelima-bellana" height="30" width="40" /></a>
</p>

