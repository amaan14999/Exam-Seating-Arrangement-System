# Exam Seating Arrangement System (ESAS) Installation Guide

## Overview

This guide provides step-by-step instructions for installing and configuring the Exam Seating Arrangement System (ESAS), a web project developed using NetBeans IDE, Java Servlet, JSP, and MySQL.

### Prerequisites:

- NetBeans IDE (Recommended version: 8.0.2, but other versions are compatible)
- MySQL Database
- MySQL Workbench

## Installation Steps

### 1. Setting Up the Environment

1. **Install NetBeans IDE**: Download and install NetBeans IDE (version 8.0.2 or later) from the official website.
2. **Install MySQL Database**: Set up MySQL on your system. Use the password `apcl123456` for database access (this is the default password used in the project, which you can change later).

### 2. Configuring the Database

3. **Launch MySQL Workbench**: Start the MySQL Workbench application.
4. **Prepare the Project**: Unzip the project folder named `ESRS.zip`.
5. **Setting Up the Database**:
   - Navigate to the `ESRS\DatabaseScript\esas.sql` location.
   - Open `esas.sql` file.
   - Copy all the SQL script from this file.
   - Paste the script into the MySQL Workbench workspace and execute it to create the `esas` database.

### 3. Configuring the Project in NetBeans

6. **Start NetBeans IDE**.
7. **Server Setup**: Ensure GlassFish Server is added in NetBeans. If not, add the GlassFish server.
8. **Open the Project**: Go to `ESRS\Project` directory and open the project in NetBeans.
9. **Database Configuration**:
   - To modify database configurations like password or host, open the `Connect` class located in the `com` package.
   - Adjust the database settings as per your requirements.
10. **Run the Project**: Execute the project in NetBeans.

### 4. Accessing the System

- **Login Credentials**:
  - Username: `admin`
  - Password: `test`

## Conclusion

Follow these steps to successfully set up and run the Exam Seating Arrangement System. For any additional help or troubleshooting, contact the developer, [Amaan](https://github.com/amaan14999)
