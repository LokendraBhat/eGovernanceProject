# eGovernanceProject
SENIOR ALLOWANCE ONLINE

# Features:

•	Registration: Allow citizens to create accounts with necessary details.
•	Login: Enable citizens to log in securely to their profile.
•	Documents upload: Citizens can quickly upload his/her images and citizenship photos which are later used for profile and validation purposes.
•	View Details: Citizens can view various details such as name, age, date of birth, and allocated senior allowances.
•	Withdraw Facilities: Citizens can withdraw their senior allowances.


# Technology Requirement
The technology stack selected for the "Senior Allowance Online System" includes:

•	Frontend: HTML, CSS, JavaScript, and Bootstrap for cross-platform development, ensuring consistency across iOS and Android devices.
•	Backend: PHP with MySQL commands
•	Database: MySQL Server of XAMPP
•	Server: Apache server

#Database 
The database includes four data tables named register_info, login_info, image_info, account_info. Various fields present in each data table are as follows:

- register_info: cit_id (primary key), full_name, phone_no, email, DOB, gender
- login_info: cit_id (primary key), email, password
- image_info: id (primary key), img_name, cit_image
- account_info: cit_id (primary key), Amount, arrival_date, withdraw_date
