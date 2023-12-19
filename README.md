# YogaClass
## ER Diagram
![Screenshot 1](/er-diagram.png)

## Overview

The **YogaClass** project is a web application developed to facilitate user registration for yoga classes. The project utilizes JSP as the backend technology, MySQL as the database, and HTML/CSS for the frontend. The architecture of the project follows the Model-View-Controller (MVC) pattern, where models, DAOs, and JSP files work cohesively to achieve the application's functionality.

## Technologies Used

- **Backend:** JSP (JavaServer Pages)
- **Database:** MySQL
- **Frontend:** HTML, CSS
## Contributor
Mohit Pathak 
## Project Structure

The project is organized based on the MVC architecture, with the following key components:

- **Model:** Defined using DAO (Data Access Object) and DAOImpl (DAO Implementation) classes, responsible for backend operations and database interactions.
- **View:** HTML forms for user input, providing a user-friendly interface.
- **Controller:** JSP files that handle user requests, create objects of backend classes, and invoke methods to process data.

## Features

1. **User Registration:** The project allows users to register for yoga classes by providing necessary information through HTML forms.

2. **Payment Integration:** The application includes a mock payment function (CompletePayment) for simulating payment processes.

3. **Change Batch Functionality:** Users have the option to change their yoga class batch.

## How to Run

1. **Database Setup:**
   - Ensure MySQL is installed.
   - Create a new database for the project.
   - Import the provided SQL script to set up the necessary tables and data.

2. **Configuration:**
   - Update database connection details in the project files to match your MySQL setup.

3. **Deployment:**
   - Deploy the project on a compatible web server (e.g., Apache Tomcat).

4. **Access the Application:**
   - Open the web browser and navigate to the deployed application.


## Project Structure

```plaintext
/YogaClass
|-- /WebContent
|   |-- /WEB-INF
|   |   |-- /classes
|   |   |   |-- (Backend class files)
|   |   |-- web.xml
|   |-- /css
|   |   |-- (CSS files)
|   |-- /jsp
|   |   |-- (JSP files)
|   |-- /WEB-INF
|   |   |-- /lib
|   |   |   |-- (JAR files)
|-- (Other project files)
