# Database Management System (DBMS) - Movie Rental Application

This is a desktop database management application developed using **C#** and **Windows Forms** for the Database Management Systems course. The project focuses on relational database design, asynchronous data access, and managing video/movie rental store operations.

## 🛠️ Tech Stack & Tools
* **Language:** C# (.NET Framework)
* **UI Framework:** Windows Forms (WinForms)
* **Database Server:** PostgreSQL
* **Data Provider:** Npgsql (PostgreSQL ADO.NET Data Provider)

## 📐 Key Implementation Details
* **Relational Database Design:** Structured tables, primary/foreign key relationships, and data integrity constraints tailored for movie catalogs, customer accounts, active rentals, and payment history.
* **Npgsql Integration:** Robust database connectivity handling queries, data retrieval, and command executions asynchronously between the desktop UI and the PostgreSQL server.
* **CRUD Operations:** Complete user interfaces designed for managing movies, customers, and tracking return dates/rentals securely with proper validation.
* **Exception Handling:** Structured try-catch blocks ensuring application stability against database connection drops or constraint violations (such as double-renting or late return flags).

## 🚀 How to Run Locally
1. Clone the repository to your local machine.
2. Open `Homework.sln` using Visual Studio.
3. Restore the NuGet packages (Visual Studio will automatically resolve dependencies from `packages.config` upon building).
4. Configure your PostgreSQL connection string in the configuration file or the database helper class.
5. Build and run the project.
