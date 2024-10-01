# Python_Flask_App_Template

This project is a simple Flask REST API with a UI for inserting and viewing records in a MySQL database hosted on AWS RDS. It supports basic CRUD operations and includes a health check endpoint.

## Features

1. **Insert Records**: Ability to add records into the database.
2. **View All Stored Records**: Retrieve and display all records stored in the database.
3. **Health Check**: Endpoint to verify the API's status.

## Steps to Deploy

1. **Clone the Repository**:
   - Run the command: 
     ```bash
     git clone https://github.com/gopika09/python_flask_app_template.git
     ```

2. **Install Dependencies**:
   - Run the command: 
     ```bash
     pip install -r requirements.txt
     ```

3. **Configure Database**:
   - Update `app.py` with your RDS connection details.

4. **Create Database Table**:
   - Access the endpoint: 
     ```
     http://<your-ip>:5000/create_table
     ```

5. **Run the Application**:
   - Start the application with:
     ```bash
     python app.py
     ```
   - Visit: 
     ```
     http://<your-ip>:5000
     ```

