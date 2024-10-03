# EpicReads - Bookstore Management System

## Demo

Watch the demo video of the project [here](https://youtu.be/59v-Nk8jbLw).

## Description

**EpicReads** is a comprehensive bookstore management system designed to handle inventory, customer orders, and sales tracking. It provides bookstore administrators with a seamless interface for managing books, while offering customers a smooth shopping experience.

### Key Features
- **User Authentication**: Secure login and registration system for customers and admins.
- **Inventory Management**: Manage book inventory including book details, author information, quantity, and price.
- **Order Management**: Handle customer orders, track status, and provide a history of purchases.
- **Sales Tracking**: Monitor sales data, with insights into total revenue and sales trends.
- **Admin Features**: Admins can add, edit, and delete books and manage user details.

---

## Technologies Used
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: JSP (Java Server Pages)
- **Database**: MySQL

---

## Project Structure
- **Frontend**: The HTML/CSS and Bootstrap files create the user interface for the bookstore, providing forms for login, registration, browsing books, and checking out. Bootstrap is used for responsive design and pre-built components.
- **Backend**: JSP is used for server-side logic, including user authentication, session management, order handling, and database interactions.
- **Database**: MySQL stores all relevant data, including user information, book details, orders, and transaction history.

---


## Setup Instructions

### Clone the Repostory

    ```bash
    git clone https://github.com/christancone/EpicReads.git

### Set Up Database
1. Install MySQL and create a new database for EpicReads.
2. Import the provided `epicreads.sql` file to set up the database schema.
3. Ensure that the MySQL connection credentials are correctly set in the `DbConnector.java` file.

### Run the Project
1. Open the project in an IDE like Eclipse or IntelliJ IDEA.
2. Set up a Tomcat server to run the JSP files.
3. Deploy the application and access it via `http://localhost:8080/epicreads` in your browser.

---

## How to Use

### Admin:
- Log in as an admin.
- Manage the bookstore inventory by adding, editing, or removing books.
- View order history and track sales data.

### Customer:
- Create an account or log in as an existing customer.
- Browse available books, add them to the cart, and place orders.
- View your order history and track the status of current orders.

---

## Outcome
EpicReads significantly streamlines the management of books and orders for bookstore admins, while also offering customers a seamless shopping experience. It helps bookstore managers efficiently track inventory, handle customer orders, and monitor sales.

