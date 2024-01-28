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

 **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/customer-crud.git


**Database Setup:**
Create a MySQL database.
Update the application.properties file in the src/main/resources folder with your database configurations.

**Build and Run Backend:**
Open the project in your preferred IDE.
Run the YourProjectApplication.java file to initiate the Spring Boot application.

**Run Frontend:**
Open the frontend folder in your code editor.
Open index.html in your browser.

**Running the Application**
Open your browser and navigate to http://localhost:8080.
Authenticate using the provided credentials.
Explore the comprehensive CRUD functionality and user-friendly UI.
Backend API Endpoints

**1.Create a Customer:**
Endpoint: /api/customers
Method: POST

**2.Update a Customer:**
Endpoint: /api/customers/{id}
Method: PUT

**3.Get a List of Customers:**
Endpoint: /api/customers
Method: GET
Query Parameters: page, size, sort, search

**4.Get a Single Customer Based on ID:**
Endpoint: /api/customers/{id}
Method: GET

**5.Delete a Customer:**
Endpoint: /api/customers/{id}
Method: DELETE

**Frontend Screens**

1.Customer List:
Navigate to / to experience an elegantly presented HTML table listing customers.
Utilize buttons for effortless customer viewing, editing, and deletion.

2.Create/Update Customer:
Visit /form to access a straightforward form for creating or updating customer records.

3.Customer Details:
Explore /details/{id} to gain intricate insights into a single customer.

**Sync Customer List from Remote API**
1.Click the "Sync" button on the Customer List screen.
2.Authenticate seamlessly using the provided credentials.
3.The application orchestrates an efficient call to a remote API, fetching the latest customer data.
4.Existing customers are gracefully updated, while new customers are seamlessly inserted into your database.


Feel empowered as you harness the capabilities of this cutting-edge Customer CRUD application. Your journey to efficient customer management begins here.
