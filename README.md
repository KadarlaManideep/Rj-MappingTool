Project Overview

This project was developed in collaboration with Raymond James Financial as part of the Comprehensive Capital Analysis and Review (CCAR) regulatory framework.

The goal was to replace manual Excel-based data mapping with a robust web application that supports real-time updates, audit tracking, and collaboration.

It enables analysts to store, map, and manage data efficiently from 40+ internal and external sources while maintaining strict governance and security

Data Mapping Tool V3

.

🚀 Business Goals

Reduce manual effort and errors in data mapping.

Improve data governance and audit readiness.

Enable controlled multi-user access with real-time edits.

Lay the foundation for future enterprise data management tools

Data Mapping Tool V3

.

🛠 Tech Stack
Layer	Technologies Used
Frontend	Angular, JavaScript, HTML, CSS, Bootstrap
Backend	C#, ASP.NET Core (MVC), Dapper
Database	Oracle SQL Developer
DevOps	GitHub, Jenkins, SonarQube (CI/CD), Unit Testing

Data Mapping Tool V3

📐 Architecture Highlights

Database-first approach using an existing Oracle schema.

MVC pattern to improve scalability and maintainability.

DTOs and Repository pattern to separate business logic and data layers.

Asynchronous operations for performance.

Optimized 20+ SQL queries to reduce join complexity and redundancy

Data Mapping Tool V3

.

✨ Key Features

Index Page: Add/Edit/Delete rows and columns, row-specific editing, search and filter columns.

Change Log Page: Full audit trail with CRUD capabilities.

Data Mapping Rule Page: Staged data mapping flow (Source → FDS PreStage → FDS Stage), allowing dynamic rule creation and updates.

User authorization tied to backend user tables for security.

Exception handling to ensure 100% data integrity

Data Mapping Tool V3

.

🧪 Development & Testing

Source control via GitHub with CI/CD pipelines.

Automated unit testing for services and repositories using Jenkins & SonarQube.

Optimized for performance and security during CRUD operations

Data Mapping Tool V3


UI/UX improvements for more intuitive mapping.

Automated data quality checks before mapping.
