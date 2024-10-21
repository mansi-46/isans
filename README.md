ISANS Program Eligibility Matrix Centralization
Problem Statement
Despite several attempts to keep our program eligibility matrix current, it remains prone to human errors and lacks the detailed breakdown needed for clients and staff to make informed decisions. As the complexity of services evolves, the need to centralize and reduce human input into the program eligibility matrix becomes paramount to improving information integrity and minimizing errors.

Our goal is to provide:

Clients with an accurate, detailed, and searchable list of programs and services they are eligible for.
Staff with a centralized, conditionally formatted matrix that minimizes the reliance on individual program areas to manually update information, reducing human errors and improving overall accuracy.
The solution must:

Be accessible from our website.
Enable staff to rely on centralized data to provide better client service.
Allow clients to easily search for programs they qualify for based on factors like immigration status, program category, etc.
Proposed Solution Overview
Key Features
Client-Facing Interface: Allows users to browse programs, filter based on eligibility, and register for services.
Staff Dashboard: Provides centralized management for program eligibility with conditional formatting to limit manual input.
Search Functionality: Improved and streamlined search and filter capabilities for users to find relevant programs based on their immigration category, eligibility, or specific themes.
Role-Based Access Control: Implements hierarchical access where different staff levels can create, update, or view programs based on their permissions.
Technologies Used
Backend:
Spring Boot (Java): Provides a robust API for managing program information, user authentication, and access control.
Frontend:
React: Provides a dynamic user interface for clients and staff, with improved filtering and data management capabilities.
Database:
MySQL: Used to store program information, user accounts, and search filters.
Additional Tools:
Postman: For API testing.
Git: For version control.
Solution Architecture
This project is structured around a client-server architecture:

Client-Side: Built using React, allowing users to register and search for programs.
Server-Side: Spring Boot application that processes requests, manages program eligibility, and handles user roles.
The project implements RESTful APIs for seamless communication between the frontend and backend.

Installation & Setup
Prerequisites:
Java 17+ (Java Development Kit)
Node.js (for running React)
MySQL (for database)
Maven (for building the Spring Boot project)

Steps to start project 

1. Open IDE terminal and navigate to directory folder "RBC"
2. Inside the "rbc/main/java/isans.hackathon.rbc" look for file name RbcApplication and run it
3. Open a new IDE window for front-end
4. in the terminal window run cmd "npm install" and "npm start"

