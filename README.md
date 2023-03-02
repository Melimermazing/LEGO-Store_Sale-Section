# LEGO-SHOP
REBOOT LABS - Database Design Project

# Project Description 
We are going to develop the database system for a sale section of LEGO® online store. The aspects of a sale section that we are developing will be the information relevant to the product in the LEGO® market. 

* The products are grouped into hierarchical categories in type of lego_block, colors and sets.
* Customers can browse products, place orders by the piece or the set.

# Database Schema

![LEGO STORE DATABASE DESIGN](https://user-images.githubusercontent.com/121776133/222481964-9b92d932-474a-45e6-918b-2de0ea48568b.png)


# Database Flowchart
#### Entitles
* customers
* history
* sales
* sales_lego_block
* lego_block
* categories
* colors
* lego_sets
* set_lego_block

#### Relationships

* The lego_block can access to categories and colors.
* The sales_lego_block can access to sales, lego_block and lego_sets
* The history can access to customers information and sales
* The set_lego_block can access to lego_block, lego_set.

# Application Platforms
This project will be done using:
* dbdiagram.io
* tableplus 
* mySQL


# Credits
This is a group project in team of 3, starting from March 2, 2023 to March 3, 2023 (2 days).

* Abian Camejo Diaz
* Jidapa Melisa Somsaen
* Victor Del Toro
