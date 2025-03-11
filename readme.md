CIM.AI - Clean India Maker (CIM)

Overview

CIM.AI is a web-based platform designed to enhance municipal waste management through digital solutions. This platform connects vendors with municipalities for efficient waste collection and disposal, promoting a cleaner environment in India.

Features

User & Admin Authentication: Secure login system using Flask and MySQL.

Vendor Management System: Facilitates vendor-municipality collaboration for waste collection services.

Interactive Dashboard: Provides insights and analytics for municipal operations.

Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: Python (Flask)

Database: MySQL

Installation

Clone the repository:

git clone https://github.com/zyzen07/CIM.AI.gits
cd CIM.AI

Install dependencies:

pip install -r requirements.txt

Set up the MySQL database:

Create a database named cim_db.

Import the provided SQL dump file into the database.

Update .env file with your database credentials:

DB_USER=<your_mysql_username>
DB_PASSWORD=<your_mysql_password>
DB_NAME=cim_db

Run the application:

python app.py

Access the website at http://localhost:5000

Usage

Signup/Login: Users and admins can register or log in.

Vendor Management: Admins can add, edit, or remove vendors. Vendors can manage their profiles and services.

Contributing

We welcome contributions! Follow these steps to contribute:

Fork the repository.

Create a new branch for your feature.

Commit your changes and push the branch.

Create a pull request.

License

This project is licensed under the MIT License.

Contact

For queries or support, contact Selva Vishnu G via LinkedIn. https://www.linkedin.com/in/selvavishnug      mailto : selvavishnug@gmail.com