# KARAD Hospital Management System - Website & Database
______________

# Link

**Website Link**: 
- http://ec2-18-221-64-219.us-east-2.compute.amazonaws.com:8080/Karad_Hospital_DB_2/
- *(as long as the tomcat7 server is running, the website is fully functional and publicly accessible)*
- Allows healthcare professionals to maintain personal and medical information regarding patients in a hospital database of patient records

______________

# Functionalities

**Some Functionalities**: 
- Admitting patients into the hospital and assigning them an available room
- Listing all patients or searching for patients with certain symptoms or illnesses
- Discharging patients once they have received medical treatment to free their assigned rooms

______________

# Usage

**Register**
- Clicking the "Register" text/button on the Home Page will bring you to the registration/signup page, where you will have to fill out the username, password, first name, last name, and email fields
- Both username and password are required fields, and the username chosen must not already exist (you will receive an appropriate error message if the entered username is already taken)
- User's entered information is saved into an SQL database in which the username is the primary key

**Login**
- Clicking the "Login" text/button on the Home Page will bring you to the login page, where you will have to enter a username and password
- Username and password MUST match the information stored in the database or else you will receive an appropriate error message (e.g. "User doesn't exist" or "Invalid password! Please try again.")

______________

# Language(s) Used

**Login page created in Eclipse using**:
- JSP
- SQL
- HTML
- CSS/Bootstrap
