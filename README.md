# airbnb-clone-project
## Project Overview
This project is a simplified version of the Airbnb platform, focusing on building a backend system for managing users, properties, and bookings. It helps learners understand real-world software development workflows using modern backend tools and practices.

## Project Goals
-Learn to collaborate using GitHub.

-Understand backend architecture and database design.

-Implement secure API development principles.

-Explore CI/CD workflows for deployment automation.

## Team Roles
-Backend Developer: Builds and manages APIs and business logic.

-Database Administrator: Designs and maintains the database structure.

-Project Manager: Coordinates team efforts and timelines.

-DevOps Engineer: Sets up CI/CD pipelines and manages deployments.

##Technology Stack

-Django: Web framework for building RESTful APIs.

-MySQL: Relational database for structured data storage.

-GraphQL: Enables flexible and efficient API queries.

-Docker: Provides containerization for consistent environments.

-GitHub Actions: Automates testing and deployment.

##Database Design

Entities:

User: id, name, email, password.

Property: id, name, location, price, owner_id.

Booking: id, user_id, property_id, start_date, end_date.

Review: id, user_id, property_id, rating, comment.

Payment: id, booking_id, amount, status.

Relationships:

A user can own multiple properties.

A property can have many bookings and reviews.

A booking is linked to a payment.

##Feature Breakdown

-User Management: Register, login, and manage profiles.

-Property Management: Add, edit, or delete listings.

-Booking System: Reserve available properties.

-Review System: Leave ratings and feedback.

-Payment System: Handle transactions securely.
