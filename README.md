# User Management System – Full Stack Web Application
## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#Key-Features)
- [Technologies Used](#technologies-used)

## Project Overview
Developed a robust full stack user management system with role-based access control using Spring Boot for backend and Angular for frontend. Implemented JWT (JSON Web Token) for secure authentication and authorization. Incorporated method-level security to restrict access to specific functionalities based on user roles (USER and ADMIN).

## Key Features
- User registration and login with encrypted credentials (BCrypt).
- Stateless authentication using JWT token passed in HTTP headers.
- Role-based access control using Spring Security annotations (@PreAuthorize, @Secured).
- Admin dashboard with ability to view, edit, and delete user data.
- User dashboard with restricted access to profile-related operations.
- Developed RESTful APIs for CRUD operations on users.
- Frontend built using Angular with reactive forms and route guards for protected views.
- Integrated error handling, token expiration handling, and session management.
- Connected to MySQL database using Spring Data JPA.

## Technologies Used
- **Frontend**: HTML, CSS, Bootstrap, Angular
- **Backend**: Spring Boot, JWT, Spring Security, REST APIs
- **Database**: MySQL
