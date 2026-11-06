🛍️ FashionStore – Online Shopping Web Application

📌 Project Overview

FashionStore is a web-based e-commerce application developed using Java, JSP, Servlets, JDBC, and MySQL. It provides users with a convenient platform to explore fashion products, manage their shopping cart, and place orders online.

The application follows the MVC (Model-View-Controller) architecture to maintain a structured and organized codebase.

✨ Features

User Registration: New users can create an account by providing their personal details.

User Login: Registered users can securely access their accounts.

Product Browsing: Explore a collection of fashion and lifestyle products.

Product Filtering: Filter products based on categories, keywords, and price range.

Product Details: View individual product information.

Shopping Cart: Add products to the cart and manage cart items.

Checkout: Proceed to checkout with delivery information.

Order Placement: Place orders using Cash on Delivery (COD).

Order Confirmation: View successful order confirmation after placing an order.

Responsive UI: User-friendly interface with CSS styling.

🛠️ Technologies Used

Category

Technologies

Frontend

HTML, CSS, JSP

Backend

Java, Jakarta Servlets

Database

MySQL

Database Connectivity

JDBC

Architecture

MVC Architecture

Build Tool

Maven

Server

Apache Tomcat 10.1

IDE

Eclipse

📂 Project Structure

FashionStore/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/fashionstore/
│       │       ├── controller/
│       │       ├── dao/
│       │       │   └── impl/
│       │       ├── model/
│       │       └── util/
│       │
│       └── webapp/
│           ├── assets/
│           │   └── css/
│           ├── image/
│           ├── WEB-INF/
│           │   ├── views/
│           │   │   ├── home.jsp
│           │   │   ├── login.jsp
│           │   │   ├── register.jsp
│           │   │   ├── products.jsp
│           │   │   ├── product-details.jsp
│           │   │   ├── cart.jsp
│           │   │   ├── checkout.jsp
│           │   │   └── order-success.jsp
│           │   └── web.xml
│           └── index.html
│
├── pom.xml
└── README.md

⚙️ Requirements

Make sure you have installed:

Java JDK 21

Apache Maven

MySQL Server

Apache Tomcat 10.1

Eclipse IDE (or any Java IDE)

🚀 Installation and Setup

1. Clone the Repository

git clone https://github.com/your-username/FashionStore.git

2. Open the Project

Import the project into Eclipse as an existing Maven project.

3. Configure MySQL Database

Create a database in MySQL:

CREATE DATABASE fashion_store;

Create the required database tables and relationships according to the application's DAO classes and SQL queries.

Note: The database schema is not included in this repository. You need to create and populate the required tables before running the application.

4. Configure Database Connection

Update the database connection settings in:

src/main/java/com/fashionstore/util/DBConnection.java

Configure your:

Database URL

MySQL username

MySQL password

For a public repository, use environment variables instead of committing database credentials.

5. Build the Project

Run the following Maven command:

mvn clean package

6. Deploy the Application

Configure Apache Tomcat 10.1 in Eclipse.

Deploy the generated FashionStore.war file.

Start the Tomcat server.

7. Run the Application

Open your browser and navigate to:

http://localhost:8080/FashionStore/

🛒 Application Workflow

User visits the FashionStore website.

User registers or logs into an account.

User browses available fashion products.

User searches and filters products.

User adds products to the shopping cart.

User proceeds to checkout.

User places an order using Cash on Delivery.

The application displays the order confirmation page.

🎯 Project Objective

The main objective of this project is to develop a functional e-commerce platform while implementing Java web development concepts such as MVC architecture, Servlets, JSP, JDBC, database operations, session management, and CRUD operations.

👩‍💻 Author

Your Name

Lakshmi P
