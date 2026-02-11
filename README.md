# gucci-database-design
## Project Overview
Presents a comprehensive relational database design for Gucci, modeling the core business operations of a global luxury fashion brand. The database integrates key functional areas including employees, customers, products, stores, manufacturing locations, orders, payments, and product lines to support both online and in-store retail activity.
## Database Scope & Objectives
The database is designed to create a logical and connected data structure across Gucci’s operations. By integrating employee records, inventory, customer purchases, and store data, the system allows managers to:

• Track inventory levels and pricing accuracy

• Locate employees across offices and retail stores

• Analyze customer purchasing behavior

• Maintain consistency between online and in-store transactions

##
After forward engineering the databases into MySQL, 5 associative tables were created to connect the tables with a many-to-many relationship. This will allow us  to make joint queries between these tables and connect the data between them. 
## Business Questions

1. Gucci wants to give extra special Christmas bonuses to their employees over 40 years old. They decided to give each of these employees a 10% raise. The company would only really use this query when handing out raises, most likely once a year.
<img width="428" height="286" alt="Screenshot 2026-02-11 at 10 35 26 AM" src="https://github.com/user-attachments/assets/827b0d1e-0be2-4c9d-aa76-b3f67416cb1a" />

2. Gucci wants to know the average price of each of their products. This is a good query to have to make sure their prices remain affordable. 
<img width="225" height="297" alt="image" src="https://github.com/user-attachments/assets/9be428cf-4e17-49b4-ad52-e0328f53dec8" />

