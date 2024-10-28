# Bike-Rental-Shop 🚲
This is a command-line Bike Rental Shop application that allows customers to rent and return bikes. The application manages customer and bike information using a PostgreSQL database and includes basic error handling and validation.

## Features
### View Available Bikes:
Customers can view available bikes listed by type and size.
### Rent a Bike:
Customers can select a bike to rent, and their information is recorded. Availability status is updated.
### Return a Bike:
Customers can return their rented bikes, and the availability status is updated accordingly.
### User-friendly Interface:
Provides clear instructions and prompts for customers to interact with the shop.

## Project Structure
### bike_rental.sh
The main bash script that controls the bike rental and return process.
### bikes.sql
The SQL dump file to set up the bikes PostgreSQL database with tables for bikes, customers, and rentals.

## Key Learnings
### Database Design
Structuring Tables for Business Logic: Developed tables for bikes, customers, and rentals, each structured to support efficient data retrieval and interaction. The database design includes foreign keys and unique constraints to maintain data integrity between rentals, bikes, and customers.

### SQL Queries
Using SQL for Business Operations: Enhanced skills in SQL by executing various queries essential for the rental operations, such as querying available bikes, verifying customer information, and recording rental details. Proficiently applied JOIN statements to extract linked data between bikes and rentals for an accurate record of current availability.

### Data Manipulation
Data Integrity and Accuracy: Practiced data manipulation techniques, including inserting, updating, and deleting records while ensuring data accuracy. Regular use of constraints and validation checks to maintain consistency within tables.

### Error Handling
SQL and Bash Scripting Debugging: Gained experience in identifying and resolving SQL syntax errors, unexpected values, and logical errors in scripts. Developed a keen attention to detail for troubleshooting both SQL statements and Bash logic.

### Bash Scripting
Automation of Customer Interaction and Rental Process: Created Bash scripts that automate the main rental operations, making it easier to check available bikes, record rentals, and manage returns. This scripting improved efficiency and provided hands-on experience in combining SQL with Bash for interactive applications.
