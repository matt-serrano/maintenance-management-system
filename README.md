# maintenance-management-system

🛠️ Maintenance Management System
📌 Overview

The Maintenance Management System is a backend application built with Java and Spring Boot that helps organizations manage and track maintenance tasks for tools, equipment, or other assets. The system follows a role-based workflow, where administrators assign maintenance tasks and users complete them using structured checklists. All completed work is recorded to provide a clear and auditable maintenance history.

This project is designed to mirror real-world maintenance and work order systems used in facilities management, IT operations, and industrial environments.

✨ Features

Role-based access control (Admin and User)

Asset and equipment management

Admin-created maintenance tasks

Task delegation and due date tracking

Checklist-based task completion

Maintenance history and audit logging

RESTful API following best practices

🧱 Architecture

The application follows a layered architecture to ensure maintainability and scalability:

Controller Layer – Handles API requests and responses

Service Layer – Contains business logic and task workflows

Repository Layer – Manages database access using Spring Data JPA

Model Layer – Represents core domain entities

This separation of concerns reflects enterprise backend development standards.

🧰 Tech Stack

Java

Spring Boot

Spring Data JPA

Spring Security (JWT authentication)

PostgreSQL / MySQL

Maven

🔐 Roles & Permissions
Role	Capabilities
Admin	Create assets and tasks, assign maintenance work, view system-wide history
User	View assigned tasks, complete checklists, submit maintenance records
