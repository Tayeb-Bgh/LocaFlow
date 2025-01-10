# LocaFlow

**LocaFlow** is a car rental management software that helps manage clients, vehicles, employees, rental contracts, vehicle status, and payments. It includes automatic notifications for maintenance, technical inspections, and insurance deadlines, as well as revenue tracking. Built with **Java** (JavaFX) and **MySQL**.

## Technologies used
- **Java** (JavaFX for UI)
- **MySQL** (Database)

## Key Features
- **Employee Management**: Add, modify, and remove employees (admin access only).
- **Vehicle Management**: Track vehicle status (available, rented, under maintenance) with automatic reminders for inspections and insurance.
- **Client Management**: Manage client info and view rental history.
- **Rental Contract Management**: Create and manage rental contracts, with notifications for late returns.
- **Revenue Tracking**: Monthly and annual revenue calculations (admin only).
- **Maintenance Management**: Track vehicle maintenance with detailed history.
- **Authentication**: Secure login system with admin-only access to sensitive data.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/locaflow.git
   cd locaflow
2. Import the MySQL database:

   Create a new MySQL database.
   Import the locaflow_database.sql script.
   Update database.properties with your MySQL credentials.

3. Install dependencies:
   ```bash
   mvn install
4. Running the project : 
   ```bash
   mvn javafx:run
