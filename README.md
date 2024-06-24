# flask_deploy
Task 1: Create Flask API file Development 
a. Create a new Flask/Django application with users.py 
b. Define a route /hello that returns the string "Hello, World!" when accessed. 
c. Implement a route /users that retrieves a list of users from a MySQL database and display as a list in html table. 
d. Implement a route /add render html page to accept input from the user and store the information in database 
e. Create a route /delete_user/<id> to delete specific data from the database 
f. Create a route /edit_user/<id> to delete specific data from the database 
g. Add error handling to handle cases when a user or resource is not found.

Task 2: Database Interaction a. Create a MySQL database with the name "users". b. Design a table "users" with the following columns:

id (int, primary key)
name (varchar)
email (varchar)
role (varchar) c. Write SQL queries to:
Insert sample data into the "users" table.
Retrieve all users from the "users" table.
Retrieve a specific user by their ID.
