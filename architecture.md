# 🏗 System Architecture

## Overview

AdminTrack is designed using a **Layered Architecture**, a widely adopted architectural pattern that promotes separation of concerns, maintainability, scalability, and testability.

By organising the application into distinct layers, each component has a clearly defined responsibility, making the system easier to understand, extend, and maintain over time.

---

# Architectural Goals

The architecture was designed with the following objectives:

- Promote separation of concerns.
- Improve maintainability.
- Support future scalability.
- Reduce coupling between components.
- Encourage code reusability.
- Simplify testing and future enhancements.

---

# High-Level Architecture

<p align="center">
    <img src="../assets/diagrams/high-level-architecture.png" alt="High-Level Architecture" width="900">
</p>

The application follows a layered request flow:

```text
Users
   │
   ▼
React Frontend
   │
   ▼
ASP.NET Core Web API
   │
   ▼
Business Services
   │
   ▼
Data Access Layer
   │
   ▼
PostgreSQL Database
```

---

# Architecture Layers

## Presentation Layer

The Presentation Layer provides the user interface through a modern web application.

Responsibilities include:

- Displaying information
- Collecting user input
- Client-side validation
- Communicating with backend services
- Providing a responsive user experience

Technology:

- React
- Bootstrap

---

## API Layer

The API Layer acts as the communication bridge between the frontend and the application's business logic.

Responsibilities include:

- Receiving client requests
- Validating incoming data
- Processing requests
- Returning structured responses

Technology:

- ASP.NET Core Web API

---

## Business Layer

The Business Layer contains the application's business rules and workflows.

Responsibilities include:

- Attendance processing
- Fine calculation
- Reporting logic
- Data validation
- Workflow coordination

This layer remains independent of the presentation layer.

---

## Data Access Layer

The Data Access Layer manages communication with the database.

Responsibilities include:

- Data retrieval
- Data persistence
- Query execution
- Transaction management

This separation ensures that business logic remains independent from data storage.

---

## Database Layer

The Database Layer provides persistent storage for application data.

Responsibilities include:

- Student records
- Attendance information
- Administrative records
- Reporting data

Technology:

- PostgreSQL

---

# Architectural Principles

AdminTrack was designed around several established software engineering principles.

## Separation of Concerns

Each layer performs a single, clearly defined responsibility.

---

## Modularity

The application is organised into logical components that can evolve independently.

---

## Scalability

The architecture supports future expansion without requiring major structural changes.

---

## Maintainability

Clear boundaries between layers make the application easier to modify and extend.

---

## Security

Security is considered throughout the application architecture through authentication, authorisation, and controlled access to system resources.

Implementation details are intentionally omitted from this public case study.

---

# Technology Stack

| Layer          | Technology            |
| -------------- | --------------------- |
| Frontend       | React 19              |
| Backend        | ASP.NET Core Web API  |
| Data Access    | Entity Framework Core |
| Database       | PostgreSQL            |
| Authentication | JWT                   |
| Styling        | Bootstrap 5           |

---

# Why Layered Architecture?

Several architectural patterns were considered during the design phase.

Layered Architecture was selected because it:

- Aligns with enterprise application development.
- Provides a clear separation between presentation and business logic.
- Simplifies maintenance.
- Supports future feature growth.
- Improves readability for development teams.
- Encourages reusable and testable components.

For a project of this scope, Layered Architecture provides an effective balance between simplicity and scalability.

---

# Future Considerations

The architecture has been designed to support future enhancements such as:

- Parent Portal
- Teacher Portal
- Mobile application
- Notification services
- Analytics dashboard
- Multi-school support

These enhancements can be incorporated without requiring fundamental architectural changes.

---

# Conclusion

The architecture of AdminTrack provides a solid foundation for building a secure, maintainable, and scalable administrative platform.

By adopting a layered architecture and established software engineering principles, the system is positioned to support both current operational needs and future organisational growth while remaining easy to maintain and extend.
