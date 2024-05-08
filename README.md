# Car-Rental-DataBase

Introduction:


Welcome to the Car Rental Database! This database is designed to efficiently manage the inventory of a car rental agency. It provides a set of tables containing crucial information about cars, customers, rentals, and more. Additionally, it includes SQL queries to extract and display relevant information from these tables.

Tables:

Cars:
Contains information about each car available for rent.
Attributes: car_id, make, model, year, color, available (boolean).
Customers:
Stores details about customers who have rented cars.
Attributes: customer_id, name, email
Rentals:
Records rental transactions, linking customers with rented cars.
Attributes: rental_id, car_id (foreign key referencing Cars table), customer_id (foreign key referencing Customers table), rental_start_date, rental_end_date.


Query Execution:
Connect to the database using your preferred SQL client.
Copy and paste the desired query into the SQL editor.
Execute the query to retrieve the requested information.
Data Management:
Use SQL commands to insert, update, or delete records as necessary to manage the database content.
