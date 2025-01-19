# Namal Blood Bank Management System (NBBMS)

## Project Overview

- The Namal Blood Bank Management System (NBBMS) is a web application developed to streamline blood donation, storage, and distribution processes within blood banks.
- It utilizes Python with Tkinter for the frontend GUI and MySQL for backend database management.

## System Requirements

### Software Requirements:
- **Operating System:** Windows
- **Development Environment:** Visual Studio Code
- **Python:** Version 3.6 or higher
- **Python Libraries:** 
  - mysql-connector-python
  - Tkinter

### Hardware Requirements:
- Standard PC with sufficient RAM and storage for development purposes

## Installation Instructions

### Step-by-Step Installation:

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   cd namal_blood_bank
Install Dependencies:

bash

pip install mysql-connector-python

pip install Tkinter
# Tkinter is usually included with Python installations
Database Setup:

Ensure MySQL is installed and running.
Create a new database named namal_blood_bank.
Import the SQL schema provided in database_schema.sql.
Usage Instructions
Running the Application:
Start the Application:

bash
python main.py
Accessing the Application:

Open a web browser and go to http://localhost:5000 (or the specified port).
Functionality:

# Admin and User Interfaces

## Admin Interface
- Manage donors, donations, blood units, recipients, networks and perform administrative tasks.

## User Interface
- View available blood bags and search for donors through blood bags.

# Code Structure

## Overview

- **`main.py`:** Entry point of the application.
- **`gui/`:** Contains all Tkinter GUI files and logic.
- **`database/`:** Scripts for database connectivity and operations.


# Team Members and Roles

- **Muhammad Asim Khan**
  - **Role:** Frontend Developer

- **Muhammad Umair**
  - **Role:** Backend Developer

- **Ayesha Tahir**
  - **Role:** Database Designer
  - **Responsibilities:** Creating and executing test cases, performing regression testing, ensuring overall software quality.

# Task Division

- Tasks are assigned and managed among team members based on individual strengths and expertise.
- Roles may include database designer, backend developer, frontend developer, tester, and project manager.
- Regular meetings will be held to track progress and address any issues.

# Credits

## Third-Party Resources

- MySQL Connector/Python: Database connectivity.
- Tkinter: GUI toolkit for Python.