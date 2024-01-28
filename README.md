Customer CRUD Application
Welcome to the Customer CRUD application! This sophisticated system allows you to seamlessly manage customer information through an intuitive user interface. The backend is powered by Spring Boot, employing robust JWT authentication, while the frontend exudes simplicity with a blend of HTML, CSS, and JS.

Table of Contents
Technologies Used
Setup
Running the Application
Backend API Endpoints
Frontend Screens
Sync Customer List from Remote API
Technologies Used
Backend: Spring Boot, Java, JWT Authentication
Frontend: HTML, CSS, JS
Setup
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/customer-crud.git
Database Setup:
Create a MySQL database.
Update the application.properties file in the src/main/resources folder with your database configurations.
Build and Run Backend:
Open the project in your preferred IDE.
Run the YourProjectApplication.java file to initiate the Spring Boot application.
Run Frontend:
Open the frontend folder in your code editor.
Open index.html in your browser.
Running the Application
Open your browser and navigate to http://localhost:8080.
Authenticate using the provided credentials.
Explore the comprehensive CRUD functionality and user-friendly UI.
Backend API Endpoints
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
Frontend Screens
Customer List:

Navigate to / to experience an elegantly presented HTML table listing customers.
Utilize buttons for effortless customer viewing, editing, and deletion.
Create/Update Customer:

Visit /form to access a straightforward form for creating or updating customer records.
Customer Details:

Explore /details/{id} to gain intricate insights into a single customer.
Sync Customer List from Remote API
Click the "Sync" button on the Customer List screen.
Authenticate seamlessly using the provided credentials.
The application orchestrates an efficient call to a remote API, fetching the latest customer data.
Existing customers are gracefully updated, while new customers are seamlessly inserted into your database.
Feel empowered as you harness the capabilities of this cutting-edge Customer CRUD application. Your journey to efficient customer management begins here.
