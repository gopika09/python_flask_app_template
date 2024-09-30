# Python_Flask_App_Template

This project is a simple Flask REST API with a UI for inserting and viewing records in a MySQL database hosted on AWS RDS. It supports basic CRUD operations and includes a health check endpoint.
Features

  1)Insert records into the database.
  2)View all stored records.
  3)Health check to verify API status.

Steps:

  1)Clone the Repository: git clone https://github.com/gopika09/python_flask_app_template.git
  2)Install Dependencies: pip install -r requirements.txt
  3)Configure Database: Update app.py with your RDS connection details.
  4)Create Database Table: Access the endpoint http://<your-server-ip>:5000/create_table.
  5)Run the Application: Start with python app.py and visit http://<your-server-ip>:5000.
