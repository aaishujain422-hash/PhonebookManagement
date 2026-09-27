# PhonebookManagement
# 📱 Phone Book Management System

A **Java-based desktop Phone Book Management System** developed using **Java Swing, JDBC, MySQL, and NetBeans**. The project provides a user-friendly graphical interface for managing contacts and demonstrates practical implementation of **Java programming, GUI development, SQL, DBMS, and database connectivity**.

## 📌 Project Overview

The Phone Book Management System is designed to digitally store and manage contact information in a structured MySQL database. Users can register and log in, add new contacts, search and edit existing contacts, delete contacts, manage favorites and groups, view contact statistics, and recover recently deleted contacts.

The project goes beyond a basic phonebook by including a **Dashboard, Favorite Contacts, Group Management, Contact Statistics, and Recently Deleted/Trash** modules.

## ✨ Features

* 🔐 User Registration & Login
* 🏠 Dashboard with contact statistics
* ➕ Add New Contact
* 🔍 Search Contacts
* ✏️ Edit Contact Information
* 🗑️ Delete Contacts
* ♻️ Recently Deleted / Trash
* ❤️ Favorite Contacts
* 👥 Contact Group Management
* 📊 Contact Statistics
* 📋 View All Contacts
* 👤 Contact Profile / Details
* 🔄 Restore Deleted Contacts
* ❌ Permanently Delete Contacts
* 🚪 Logout / Exit

## 🛠️ Technologies Used

| Technology       | Purpose                              |
| ---------------- | ------------------------------------ |
| **Java**         | Application logic and functionality  |
| **Java Swing**   | Graphical User Interface             |
| **JDBC**         | Java–MySQL database connectivity     |
| **MySQL**        | Database management and data storage |
| **NetBeans IDE** | Development environment              |
| **SQL**          | Database queries and operations      |

## 🗄️ Database

The project uses a MySQL database named `phonebookmanagement`.

Main tables include:

* `login` – Stores user login information
* `add_contact` – Stores active contact details
* `favorite_contact` – Manages favorite contacts
* `contact_groups` – Stores contact groups
* `contact_statistics` – Stores contact statistics
* `trash_contact` – Stores recently deleted contacts

The application performs database operations such as:

* `INSERT`
* `SELECT`
* `UPDATE`
* `DELETE`
* `COUNT`
* `GROUP BY`

## 🔄 Application Workflow

```text
Welcome Screen
      ↓
Login / Registration
      ↓
Dashboard / Home
      ↓
Contact Management
 ┌────┼─────┬──────┬─────────┐
 ↓    ↓     ↓      ↓         ↓
Add  Search Edit  Delete  Favorites
                         ↓
                       Trash
                         ↓
                  Restore / Delete
```

User input is collected through Java Swing components. Java processes the input and sends SQL queries to MySQL through JDBC. The database performs the requested operation, and the result is displayed back to the user through the application interface.

## 📂 Main Java Modules

Some of the major classes/modules included in the project are:

* `Welcome.java`
* `Login.java`
* `Registration.java`
* `Home.java`
* `Dashboard.java`
* `ConnectionClass.java`
* `EntryData.java`
* `SearchData.java`
* `SearchDatatable.java`
* `EditData.java`
* `DeleteContact.java`
* `FavoriteContacts.java`
* `ContactStatistics.java`
* `GroupManagement.java`
* `ViewGroups.java`
* `ViewContacts.java`
* `TrashContacts.java`
* `ContactProfile.java`

Each module handles a specific part of the application, making the project organized and easier to maintain.

## ⭐ What Makes This Project Different?

Unlike a basic CRUD phonebook, this project includes additional management features such as:

* **Dashboard** for an overview of the phonebook
* **Favorites** for quick access to important contacts
* **Groups** for better contact organization
* **Statistics** for database insights
* **Recently Deleted/Trash** for recovering deleted contacts
* **Contact Profiles** for detailed information
* **Login and Registration** for controlled application access

## 🎯 Learning Objectives

This project helped demonstrate practical knowledge of:

* Object-Oriented Programming in Java
* Java Swing GUI development
* Event handling using `ActionListener`
* JDBC database connectivity
* SQL queries
* MySQL database design
* CRUD operations
* Relational database concepts
* Java–DBMS integration
* Form validation and data processing

## 🚀 Future Improvements

Possible future enhancements include:

* Password encryption/hashing
* Advanced contact search and filtering
* Contact profile pictures
* Import/export contacts
* Database backup and restore
* Birthday and anniversary reminders
* Cloud synchronization
* Multi-user access
* Improved input validation and security

## 👨‍💻 Project Type

**Academic Project – Java + DBMS**

This project was developed to demonstrate the integration of a **Java desktop application with a MySQL relational database** while implementing a practical real-world contact management system.

---

## 📄 Documentation

Detailed project documentation covering the system design, workflow, database, features, screenshots, testing, challenges, and future scope is included with the project.
