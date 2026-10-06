Here is a simple README you can submit with the REST API program.
README – User Management REST API
User Management REST API
Objective
Create a REST API that manages user data using Python and Flask.
Tools Used
Python
Flask
Postman / cURL
Description
This project demonstrates a simple REST API for managing user information. It performs CRUD operations using four HTTP methods:
GET – Retrieve user data
POST – Add a new user
PUT – Update existing user information
DELETE – Delete a user
Installation
Install Flask using the following command:
pip install flask
How to Run
Save the Python program as app.py.
Open the terminal in the project folder.
Run:
python app.py
The application will start at:
http://127.0.0.1:5000
API Endpoints
Method
Endpoint
Description
GET
/users
Get all users
POST
/users
Add a new user
PUT
/users/<id>
Update a user
DELETE
/users/<id>
Delete a user
Example POST Data
{
    "name": "Anjali",
    "email": "anjali@gmail.com"
}
Expected Output
GET
Returns the list of users.
POST
Returns the newly created user with its ID.
PUT
Returns the updated user information.
DELETE
Returns:
{
    "message": "User deleted successfully"
}
Result
The REST API was successfully created using Flask. The application performs GET, POST, PUT, and DELETE operations for managing user data.
Conclusion
This project provides a basic understanding of REST API development using Python Flask and demonstrates how CRUD operations can be implemented through HTTP methods.
