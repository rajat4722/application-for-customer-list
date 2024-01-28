# Customer CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) application for managing customer information. The backend is implemented using Spring Boot with JWT authentication, and the frontend is built using basic HTML, CSS, and JS.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Running the Application](#running-the-application)
- [Backend API Endpoints](#backend-api-endpoints)
- [Frontend Screens](#frontend-screens)
- [Sync Customer List from Remote API](#sync-customer-list-from-remote-api)

## Technologies Used

- Backend: Spring Boot, Java, JWT Authentication
- Frontend: HTML, CSS, JS

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/customer-crud.git

   Database Setup:

**Create a MySQL database and update the application.properties file in the src/main/resources folder with your database configurations.**
Build and Run Backend:

Open the project in your favorite IDE.
Run the YourProjectApplication.java file to start the Spring Boot application.
Run Frontend:

Open the frontend folder in your code editor.
Open index.html in your browser.
Running the Application
Open your browser and go to http://localhost:8080.
Authenticate using the provided credentials.
Explore the CRUD functionality and UI.
**Backend API Endpoints**
Create a Customer:

Endpoint: /api/customers
Method: POST
Update a Customer:

Endpoint: /api/customers/{id}
Method: PUT
Get a List of Customers:

Endpoint: /api/customers
Method: GET
Query Parameters: page, size, sort, search
Get a Single Customer Based on ID:

Endpoint: /api/customers/{id}
Method: GET
Delete a Customer:

Endpoint: /api/customers/{id}
Method: DELETE
**Frontend Screens**
Customer List:

Navigate to / to view a basic HTML table listing customers.
Use buttons to view, edit, and delete customers.
Create/Update Customer:

Navigate to /form to access a simple form to create or update a customer.
Customer Details:

Navigate to /details/{id} to view details of a single customer.
**Sync Customer List from Remote API**
Click the "Sync" button on the Customer List screen.
Authenticate using the provided credentials.
The application will call a remote API to fetch customer data.
If a customer already exists, it will be updated; otherwise, a new customer will be inserted.
