# SyncSecure - Centralized Account Management System

## Overview
SyncSecure is an essential tool designed for organizations to manage account access and authentication securely. It streamlines the process of user authentication, password management, and access permissions, ensuring enhanced operational security and efficiency.

![Main Page](https://github.com/shahzada-shah/syncsecure/blob/main/assets/login.png)

## Tech Stack
- **Frontend**: ReactJS
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL (RDS)
- **Hosting:** AWS (S3, RDS, Elastic Beanstalk)
- **State Management:** React Context API
- **Routing:** React Router with Protected Routes
- **Styling:** Styled Components
- **API Calls:** Axios to interact with custom Backend API

## Special Note
Leveraging the PERN stack integrated with AWS, SyncSecure provides a resilient and scalable platform tailored for managing sensitive data and user accounts in dynamic organizational settings.

## Security Features
1. **Password Hashing:** Utilizes the scrypt algorithm for secure password hashing to ensure data integrity and mitigate risks associated with password theft.
2. **Role-Based Access Control (RBAC):** Access to certain functionalities such as creating or updating user information is restricted based on user roles defined in the database, ensuring that only authorized personnel can perform sensitive operations.

![Main Page](https://github.com/shahzada-shah/syncsecure/blob/main/assets/table.png)
![Main Page](https://github.com/shahzada-shah/syncsecure/blob/main/assets/createp1.png)
![Main Page](https://github.com/shahzada-shah/syncsecure/blob/main/assets/createp2.png)
![Main Page](https://github.com/shahzada-shah/syncsecure/blob/main/assets/createp3.png)

## Functionalities
1. **User Authentication:** Secure login system incorporating advanced hashing to protect credentials.
2. **Password Management:** Features allowing users to securely reset and update their passwords, validated in real-time against security standards.
3. **Access Control:** Manages user roles and permissions efficiently, with granular control over who can view or modify sensitive data.
4. **Enhanced Security:** Implements stringent security protocols to safeguard data and user interactions against potential threats.

![Main Page](https://github.com/shahzada-shah/syncsecure/blob/main/assets/update.png)
![Main Page](https://github.com/shahzada-shah/syncsecure/blob/main/assets/hasheddata.png)

## Live Demo on AWS
Explore the capabilities of SyncSecure with our live demo hosted on AWS:

URL: [SyncSecure Live Demo](http://amsclient.s3-website-us-east-1.amazonaws.com/#)

Test Credentials: <br/>
Username: hiringmanager <br/>
Password: hiringmanager@

Note: The demo account is configured with restricted access to demonstrate user and password management features safely.
