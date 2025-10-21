<!-- AIRBNB CLONE -->

# Airbnb Clone Project

<!-- Overview of project -->
## Overview
The Airbnb Clone Project is a full-stack web application designed to replicate the functionality of a modern booking platform like Airbnb. The project's primary goal is to provide hands-on experience in building scalable, and production-ready systems while reinforcing the principles of collaborative software development.

Through this project, I aim to deepen my understanding of backend architecture, database design, API development, and deployment workflows. I'll be exploring how different technologies integrage to create a cohesive system that can support real-world use cases such as use authentication, property listings and booking management.

<!-- Project goals -->
## Project Goals
- Learn full-stack architecture by designing and implementing a functional booking system from the ground up.
- Gain practical experience with backend frameworks, database design, and API development.
- Apply secure development practices to protect data and ensure system integrity.
- Automate workflows using CI/CD pipelines for efficient testing and deployment.
- Collaborate using Github to simulate professional development environments.

<!-- Tech stach -->
## Technology Stack
- **Django**: A high-level Python Webframework used to build RESTful API.
- **Django Rest Framework**: Provides tools for creating and managing RESTful APIs.
- **PostgreSQL**: A powerfull relational database used for data storage.
- **GraphQL**: Allows for flexible and efficient querying of data.
- **Celery**: For handling asynchronous taks such as sending notifications or processing payments.
- **Redis**: Used for caching and session management.
- **Docker**: Containerization tool for consistent development and deployment environments.
- **CI/CD Pipelines**: Automated pipelines for testing and deploying code changes.

<!-- Team roles -->
## Team Roles
- **Backend Developer**: Responsible for implementing API endpoints, database schemas, and business logic.
- **Database Administrator**: Manages database design, indexing, and optimizations.
- **DevOps Engineer**: Handles deployment, monitoring, and scaling of the backend services.
- **QA Engineer**: Ensures the backend functionalities are thoroughly tested and meet quality standards.

## Database Design
### Key Entities
- Users - Fields(Id, Name, email, location). Relationships(Can have multiple properties, can have multiple bookings, can have multiple reviews)
- Properties - Fields(id, name, location, price, description, status)
- Bookings - Fields(id, property, user, created_at, status). Relationships(Can only have on property, can only have one user)
- Reviews - Fields(id, user, text). Relationships(Can have only one user)
- Payments - Fields(id, status, booking)

## Feature Breakdown
- **User Authentication**: Register new users, authenticate, and manager user profiles.
- **Property Management**: Crete, update, retreive, and delete property listings.
- **Booking System**: Make, update, and manage bookings, including check-in and check-out details.
- **Payment Processing**: Handle payment transactions related to bookings.
- **Review System**: Post and manage review for properties.
- **Datbase Optimizations**: **Indexing** - Implement indexes for fast retrieval of frequently accessed data and **Caching** - Use caching strategies to recue database oad an improve performance.
