Project Title:
Inventory Tracking System

Project Description
This project implements a full-featured Inventory Tracking System using only MySQL. It allows businesses to track products, their quantities at various storage locations, their suppliers, and their movement between locations. It supports:
•	Categorizing products
•	Associating suppliers with products
•	Storing inventory per location
•	Recording inventory transfers
•	Employee assignments to locations

      How to Run/Setup the Project
1.	Install MySQL Server on your system.
2.	Use a client like MySQL Workbench, phpMyAdmin, or command line.
3.	Run the SQL script below in your database client.


Relationships Summary
Relationship Type	From Table	To Table	Description
1-to-Many	categories	products	Each category has many products
1-to-Many	suppliers	products	Each supplier can supply many products
Many-to-Many	products ↔ locations	via inventory	Each product can exist in many locations
One-to-One	employees	locations	Each location is managed by one employee
One-to-Many	products	inventory_movements	Track movement history of products


ERD
![image](https://github.com/user-attachments/assets/1af28cb1-bd92-49f6-94cc-85a8da003ee6)







 

