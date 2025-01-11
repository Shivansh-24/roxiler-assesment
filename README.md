A web application enabling users to submit a rating of any store registered on this platform. The rating will be between 1 to 5 Tech Stack Ruby on Rails Database: Any relational database Requirement We require a web application enabling users to submit a rating of any store registered on this platform. The rating will be between 1 to 5. We will need a single login for all types of users and based on the user’s role he will see the functionalities on the page after login. For normal users provide a signup page to register on the platform. User Personas (Roles):

System Admin
Normal User
Store Owner System Admin Functionalities:
Admin can add stores, normal users, and admin users in the system
Show one dashboard page to the admin user with the following details
Total Users
Total Stores
Total Users Submitted Rating
The user addition form will have the following fields
Name
Email
Password
Address
During the store listing display, the following fields
Name, Email, Address, Rating
During the normal users and admin users listing display, the following fields
Name, Email, Address, and Role
All the listings should have an option to apply a filter on these fields
Name, email, address, and Role
Allow an option for Admin user to see the following details of all types of users
Name, email, address, and role
Rating - in case the user type is Store Owner
Provide an option to logout from the system
Normal User Functionalities:

The user should be able to log in and sign up to the platform
The signup form will have the following fields
Name, Email, Address, Password
Provide an option to user to change the password after login
The user should be able to see the list of all registered stores
Allow users to search the store based on name and address
Store listing will have to list the following details in the table.
Name
Address
Overall ratings
My submitted rating
Option to submit my rating
Option to modify my submitted rating
Allow users to submit ratings between 1 to 5 to individual store
Provide an option to logout from the system Store Owner User Functionalities:
The user should be able to log in to the platform
After login user should be able to change the password
On the dashboard, he should be able to see the list of users who have submitted the rating to his store
On the dashboard display the average total submitted ratings to his store
Provide an option to logout from the system
Validations: (validations should be present on all forms) ● The name length should be 60 characters max and 20 characters min ● The Address length should be 400 characters max ● The password length max 16 and 8 min, it should have at least 1 upper, and 1 special character in it. ● Email address validation should be there in the email field.

Note:

All the tables should have sorting (ascending/descending) functionality on important fields like name, email, etc.
Follow best practices at both the sides frontend and backend.
Best practices need to be followed on table schema design on the database side.
