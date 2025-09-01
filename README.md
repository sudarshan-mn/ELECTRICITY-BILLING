📌 Project Overview

The Electricity Billing System is a Java-based desktop application built using Swing and AWT. It allows administrators and customers to manage electricity billing, view details, generate bills, and make payments.

This project is structured as a NetBeans IDE project and uses Java + MySQL for backend operations.

📂 Project Structure
Electricity-Billing-System/
│── build.xml                  # Apache Ant build file (NetBeans)
│── manifest.mf                 # Project manifest
│── src/electricity/billing/system/
│     ├── Login.java
│     ├── Signup.java
│     ├── CustomerDetails.java
│     ├── GenerateBill.java
│     ├── PayBill.java
│     ├── Project.java          # Main class
│     └── ... other files
│── build/classes/icon/         # Image assets for UI

⚙️ Requirements

Java JDK 8 or higher

NetBeans IDE (recommended) or any IDE with Ant support

MySQL Database

JDBC driver for MySQL (e.g., mysql-connector-java-x.x.x.jar)

🚀 How to Run
Option 1: Using NetBeans (Recommended)

Open NetBeans IDE.

Go to File > Open Project.

Select the folder Electricity-Billing-System.

Right-click on the project → Run.

The main class is usually Project.java.

Option 2: Using Command Line

Open terminal inside the project folder.

Compile:

javac -cp "lib/*" src/electricity/billing/system/*.java -d bin


Run:

java -cp "bin:lib/*" electricity.billing.system.Project

🛠 Database Setup

Install MySQL and create a database (e.g., ebs).

Import the required SQL script (if provided) or manually create necessary tables (customer, bill, meter, etc.).

Update database connection details in Conn.java:

Connection c = DriverManager.getConnection("jdbc:mysql://localhost:3306/ebs", "username", "password");

📸 Screenshots (UI contains icons in build/classes/icon/)

Login screen

Customer registration

Bill generation

Payment window

👨‍💻 Authors

This project was developed as a Java Swing & Database Management System (DBMS) project for learning and demonstration purposes.
