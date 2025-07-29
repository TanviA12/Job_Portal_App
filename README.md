 Job Portal System

A full-stack web application built with Java, Spring Boot, Spring Security, Thymeleaf, and MySQL that allows employers to post job openings and applicants to apply for jobs and track application status.


 Overview

This project simulates a real-world job board with two types of users:

- **Employers** can post, view, and manage job listings.
- **Applicants** can browse jobs, apply for positions, and track their application status.

Built using the Spring Boot framework, this project demonstrates key backend and frontend development concepts including RESTful APIs, MVC architecture, role-based access, authentication, and database integration.



 Tech Stack

| Layer        | Technology                      |
|--------------|----------------------------------|
| Language     | Java                             |
| Framework    | Spring Boot, Spring Security     |
| View Engine  | Thymeleaf                        |
| Database     | MySQL, Spring Data JPA           |
| Frontend     | HTML, CSS (with Bootstrap)       |
| Build Tool   | Maven                            |
| Dev Tools    | IntelliJ / Eclipse, Postman      |
| Hosting      | GitHub                           |


 Features

- ✅ User registration and login
- ✅ Role-based access for Employers and Applicants
- ✅ Employer dashboard to post/view/manage jobs
- ✅ Applicant dashboard to view/apply to jobs
- ✅ Application status tracking (pending/accepted/rejected)
- ✅ Secure password hashing using BCrypt
- ✅ Search and filter jobs by title/location
- ✅ MVC-based structured codebase


 Database Schema

**Tables:**
- `users`: Stores user credentials and roles
- `jobs`: Contains job postings by employers
- `applications`: Tracks which user applied to which job and the status

(Relationships handled using JPA annotations)

