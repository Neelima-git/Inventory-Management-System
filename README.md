# Inventory-Management-System
This repository is having all the codes used in AI/ML Skill India scholarship assignment on Inventory Management System. 

### About the repository
The project is implemented using JSON, NoSQL database and File Handling.

### Files 
1. Add products: This file contains code for adding or updating products in the repository.
2. Purchasing: This file contains code for nuying products form inventory.
3. Products.json: This file has details of all the products in the inventory.
4. Sales.jsonL This file has transaction history of all the purchases.

### Features 
### In Adding Products file
1. Add new items into inventory if the product doesn't already exist in Inventory.
2. Update the number of units available for a product if the product already exists in inventory.
### In Purchasing products
1. Check for the user enquired product in the inventory.
    1. If product exists proceed further.
    2. If no, inform user that the product isn't available in inventory.
2. Enquire number of units/quantity for the product that the user want to buy.
    1. If that many units are available proceed further.
    2. If no, then inform user about the number of units available for purchase in the inventory.
3. Display the product name, unit price and bill amount for the user.
4. Ask for the payment method cash/card. 
5. If sekected card then ask for PIN number and details.
