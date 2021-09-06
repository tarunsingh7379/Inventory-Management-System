# Inventory-Management-System
This repository is having all the codes used in AI/ML Skill India Scholarship Assignment on Inventory Management System.

## About The Repository
You will learn JSON, NoSQL Databases, File Handling.

## Files
* ### record.json
  This file is containing all the product details that are available in the inventory.
* ### sales.json
  This file is containing all the sales that are made till now.
* ### Adding_new_Products.ipynb
  From this file we can purchase products for the inventory. It will purchase product for the inventory and add the product details in the record.json file.
* ### Purchasing_Products.ipynb
  From this file a user can purchase products from the inventory and the purchased product details will be added in the sales.json file.

## Features
* ### Adding_new_Products.ipynb
  * We can add products in the inventory and their details will be updated in the record.json file. 
  * If the product is already present in the inventory, then its quantity will be increased by the quantity we will add.
* ### Purchasing_Products.ipynb
  * It will show a menu that contains product id and name of all the products that are available in the inventory.
  * A user can purchase products from the inventory and the Bill will be shown to him.
  * The bill contains name of the product, price of the product, quantity of the product and the total bill amount that the user has to pay.
  * If a user try to purchase a product that is currently not available in the inventory, a proper message will be shown to him that will say this product is out of stock.
  * If a user try to purchase a product but the user required quantity of the product is not available in the inventory, a message will be shown to him that will say we have this amount of product if you want to buy only this amount of product say yes else no.
  * For each successful transaction, the details of the purchased product will be added in the sales.json file.
* ### record.json
  Record.json contains several attributes of the products that are-
  * Product id
  * Name
  * Price
  * Quantity
  * Category of the product
  * Rating of the product
* ### sales.json
  Sales.json files contains several attributes of the transaction that are-
  * Transaction id
  * Product id
  * Name of the product
  * Quantity of the product
  * Price of the product
  * Total Bill Amount
  * Time at which transaction has made

## About Me
I am Tarun Singh. I am currently pursuing B.Tech as a third year student. I am a competitive programmer. I love to do coding. My primary language for coding is C++. 



