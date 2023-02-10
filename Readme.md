Employee Management System
Introduction

This project is a web-based application that allows you to manage your employees efficiently. The system provides a platform for you to add, update and delete employee records, and view a list of employees with their details. The project is developed using Java, MySql, and HTML, CSS.

Requirements

Before you start using the Employee Management System, make sure you have the following software installed on your computer:

Java Development Kit (JDK) 8 or above

MySQL Server 5.7 or above
Any web browser (Google Chrome, Mozilla Firefox, etc.)
Installation
Clone the repository to your local machine using the following command:

bash
Copy code
git clone [https://github.com/[YOUR_USERNAME]/Employee-Management-System.git]
Import the project into your Java IDE (Eclipse, IntelliJ IDEA, etc.).

Create a database in MySql and execute the SQL scripts in the sql folder to create the necessary tables.

Update the database configuration in the [src/main/resources/application.properties file] with your database details.

Run the project using your Java IDE or by using the following command:

Copy code
mvn spring-boot:run
Open a web browser and navigate to [http://localhost:8080] to access the Employee Management System.

Features
Add, update, and delete employee records
View a list of employees with their details
Search employees by name
Sort employees by ID, name, or salary
Pagination to view a limited number of employees at a time
Contribution
We welcome contributions to the Employee Management System. If you have any suggestions or found any bugs, please open an issue or a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
