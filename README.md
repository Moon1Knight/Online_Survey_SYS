Survey-Sheet
====================

SurveySheet is an online survey system for create and publish online surveys in minutes, and view results graphically and in real time. 

# Features
Survey Creation: Easily design custom surveys with various question types.
Real-Time Results: View survey responses graphically as they are submitted.
User Management: Administer user roles and permissions for survey participation and creation.

##Installation
Clone the Repository
Navigate to the Project Directory
###Set Up the Database:
Ensure you have MySQL installed.
Create a database named SurveySheet.
Import the provided SQL script to set up the necessary tables.
###Configure the Application:
Update the database connection settings in the application.properties file.
###Build and Run the Application:
**mvn clean install**
mvn spring-boot:run

##Usage
Access the application at http://localhost:8080.
Register a new account or log in with existing credentials.
Create, distribute, and analyze surveys through the user-friendly interface.

##Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

##License
This project is licensed under the MIT License. See the LICENSE file for details.

##Acknowledgments
Inspired by the need for efficient online survey solutions.
Utilizes Spring Boot and Thymeleaf for rapid development.

::contentReference[oaicite:0]{index=0}
