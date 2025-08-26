



# Customer Complaint Analysis System

## Project Overview  
A Java console application for managing customer complaints backed by a MySQL database. Employees can manage customers and complaints, while customers can register complaints directly. The system uses JDBC to connect Java with MySQL.

---

## Features  
- **Employee Functions:** Add customers, register complaints, view complaints, update complaint status.  
- **Customer Functions:** Register complaints.  
- Fully relational database with customers, products, employees, orders, and complaints.

---

## Technologies  
- Java SE (JDK 8+)  
- JDBC API  
- MySQL  
- Console I/O  

---

## Setup

### Database  
1. Install and start MySQL.  
2. Run `customer_complaint_analysis.sql` to create schema and sample data:


### Java Application  
1. Configure JDK and import project into your IDE.  
2. Add MySQL JDBC driver (e.g. `mysql-connector-java.jar`) to your project libraries.  
3. Update database credentials inside `ComplaintManagementSystem.java`:
4. Compile and run the project from your terminal or IDE.

---

## Usage  
Run the app, choose role (Employee/Customer), and navigate the interactive menus to perform actions.

---

## Project Files  
- `ComplaintManagementSystem.java`: Java source code with JDBC logic and menus.  
- `customer_complaint_analysis.sql`: SQL script for database creation and sample data.

---

## Notes  
- Basic error handling and console user interface for demonstration.  
- Ensure MySQL server is running before launching the app.  
- Extensible for enhancements such as complaint status viewing by customers.

---

## License  
Open-source for educational use.







