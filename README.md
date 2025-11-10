🚗 Showroom Management System
📋 Project Overview

The Showroom Management System is a simple Java-based console application that helps manage showrooms, employees, and cars efficiently.
This system allows the user to add and view details of showrooms, employees, and cars through an interactive menu-driven interface.

🧩 Features

➕ Add new Showroom, Employee, or Car
📋 View details of all Showrooms, Employees, and Cars
🏷️ Auto-generates unique Employee IDs using UUID
💾 Stores information temporarily using object arrays
🧠 Demonstrates Object-Oriented Programming (OOP) principles such as:
Inheritance
Abstraction (interface)
Encapsulation
Polymorphism

🧱 Project Structure
Showroom-Management-System/
│
├── Main.java
├── Showroom.java
├── Employees.java
├── Cars.java
└── README.md

🧠 Classes and Their Roles
1. Main.java
   
Acts as the entry point of the program.
Displays the main menu and handles user input.
Allows adding and viewing details of showrooms, employees, and cars.

3. Showroom.java
Stores details about each showroom such as:

Name
Address
Manager name
Number of employees
Cars in stock
Implements utility interface for setting and getting details.

3. Employees.java
Manages employee data such as:

Employee ID (auto-generated)
Name
Age
Department
Showroom name
Inherits from Showroom class and implements utility.

4. Cars.java
Holds car information including:

Name
Color
Fuel type
Price
Car type
Transmission type
Inherits from Showroom class and implements utility.

5. utility Interface
Defines two abstract methods:

public void get_details();
public void set_details();

Implemented by all major classes to maintain a consistent structure.

🧑‍💻 How to Run

Clone or download this repository.

Open the project in your preferred IDE (e.g., IntelliJ, Eclipse, VS Code).

Compile and run the Main.java file.

Follow the on-screen instructions to:

Add Showrooms
Add Employees
Add Cars
View details

🖼️ Sample Output
======================= *** WELCOME TO SHOWROOM MANAGEMENT SYSTEM *** =======================

=============================== *** ENTER YOUR CHOICE *** ===============================
1].ADD SHOWROOMS        2].ADD EMPLOYEES        3].ADD CARS
4].GET SHOWROOMS        5].GET EMPLOYEES        6].GET CARS
=============================== *** ENTER 0 TO EXIT *** ===============================

> 1
======================= *** ENTER SHOWROOM DETAILS *** =======================
SHOWROOM NAME: ABC Motors
SHOWROOM ADDRESS: Chennai
MANAGER NAME: Ramesh
TOTAL NO OF EMPLOYEES: 10
TOTAL CARS IN STOCK: 25

💡 Concepts Used

Classes and Objects
Inheritance
Interfaces
Method Overriding
Encapsulation
Array-based data handling
UUID generation

🧾 Future Enhancements

Add file or database storage for data persistence
Implement search, update, and delete functionalities
Create a GUI version using JavaFX or Swing
Add authentication (Admin/User)

🧑‍🏫 Author

Pavithra R.K
🎓 CSE Graduate | 💻 Java Developer | 🌸 Passionate Learner
