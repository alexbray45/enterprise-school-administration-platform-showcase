# 🎓 AdminTrack

<!-- <p align="center">

<img src="assets/banner/admintrack-banner.png" width="100%">

</p> -->

<p align="center">

### Enterprise School Administration Platform

Digitising administrative operations through modern software engineering.

Designed for a secondary educational institution.

</p>

---

<p align="center">

![Status](https://img.shields.io/badge/Status-Design%20Complete-success)

![Architecture](https://img.shields.io/badge/Architecture-Layered-blue)

![Frontend](https://img.shields.io/badge/Frontend-React%2019-61DAFB)

![Backend](https://img.shields.io/badge/Backend-ASP.NET%20Core%209-512BD4)

![Database](https://img.shields.io/badge/Database-PostgreSQL-336791)

![Documentation](https://img.shields.io/badge/Documentation-Complete-orange)

</p>

> **Note**
>
> This repository is intended as a software engineering case study.
> Documentation has been intentionally limited to high-level design concepts.
> Implementation details, infrastructure configuration, source code, and sensitive technical information remain private.

---

# 🔒 Repository Status

The implementation source code for AdminTrack is intentionally maintained in a **private repository**.

This public repository has been created as an engineering case study to showcase the complete software engineering process behind the project, including:

- Business Analysis
- Requirements Engineering
- System Architecture
- UI/UX Design
- Engineering Decisions
- Software Development Process

The implementation source code, infrastructure configuration, database schema, and deployment details remain private.

## 📖 Overview

AdminTrack is an enterprise school administration platform designed to modernise attendance administration at Legae Academy.

Rather than replacing classroom attendance, AdminTrack digitises the administrative processes that occur after attendance has been taken, including absence management, lateness tracking, fine management, reporting, and audit logging.

This repository serves as a software engineering case study documenting the complete design, planning, and architecture of the system.

The implementation source code is maintained in a private repository.

## 📌 Executive Summary

Many schools continue to rely on paper-based administrative processes for managing student attendance records, lateness, fines, and reporting. While classroom attendance remains effective on paper, the surrounding administrative workflows often involve duplicated effort, delayed communication, and fragmented record keeping.

AdminTrack was designed to streamline these workflows by providing a secure, scalable, and maintainable web-based administration platform. The project follows a structured software engineering process, from business analysis and requirements engineering through architecture, database design, API specification, UI/UX planning, and technical documentation.

# 📊 Project Highlights

| Metric                  |                Value |
| ----------------------- | -------------------: |
| User Roles              |                    4 |
| Core Modules            |                    8 |
| Functional Requirements |                  40+ |
| User Stories            |                  20+ |
| Planned Screens         |                  10+ |
| Architecture            | Layered Architecture |
| Methodology             |          Agile Scrum |
| Documentation           |             Complete |

## 🚩 Business Problem

Current attendance administration at Legae Academy involves multiple manual processes.

• Teachers record attendance using paper registers.

• Absence forms are completed manually.

• Prefects separately record late arrivals.

• Administrative staff manually calculate fines.

• Reports are compiled from multiple paper records.

This process creates unnecessary duplication, delays, and inconsistencies.

---

## 🔄 Existing Workflow

Teacher Records Attendance

↓

Absent Students Written onto Paper Forms

↓

Assistant Vice Principal Collects Forms

↓

Prefects Record Late Students

↓

Attendance Administrator Calculates Fines

↓

Reports Generated Manually

## 💡 Proposed Solution

AdminTrack digitises the administrative workflow while preserving classroom attendance procedures.

The platform provides:

• Student record management

• Absence administration

• Lateness tracking

• Automatic fine calculation

• Reporting dashboard

• Audit logging

• Role-based access control

• Historical attendance records

---

# ✨ Key Features

| Feature                   | Description                                                |
| ------------------------- | ---------------------------------------------------------- |
| Student Import            | Import and manage student records from school data sources |
| Absence Management        | Record, update, and monitor student absences               |
| Lateness Tracking         | Record daily student lateness and maintain history         |
| Fine Management           | Automatically calculate and manage lateness fines          |
| Dashboard                 | View attendance statistics and administrative summaries    |
| Reports                   | Generate attendance and financial reports                  |
| Audit Logging             | Track important user activities throughout the system      |
| Role-Based Access Control | Secure access based on user roles and permissions          |

---

# 👥 User Roles

| Role                     | Responsibilities                                                                |
| ------------------------ | ------------------------------------------------------------------------------- |
| Attendance Administrator | Daily attendance administration, lateness recording, fine management, reporting |
| Assistant Vice Principal | Monitor absences, approve attendance-related activities, oversee administration |
| Principal                | Review reports, monitor attendance trends, access dashboard analytics           |
| System Administrator     | Manage users, permissions, system configuration, and security                   |

---

# 🏗 System Architecture

AdminTrack adopts a layered architecture to promote separation of concerns, maintainability, and scalability. The diagram below illustrates the high-level flow between users, the application, and the data layer.

<p align="center">
  <img src="./assets/diagrams/system-architecture.png"
       alt="System Architecture"
       width="900">
</p>

```text
Users
   │
   ▼
React Frontend
   │
   ▼
REST API
   │
   ▼
ASP.NET Core Web API
   │
   ▼
Entity Framework Core
   │
   ▼
PostgreSQL Database
```

📄 **Further Reading:** [Architecture Documentation](docs/architecture.md)

---

# 💻 Technology Stack

| Layer           | Technology             |
| --------------- | ---------------------- |
| Frontend        | React 19               |
| Backend         | ASP.NET Core 9 Web API |
| Database        | PostgreSQL             |
| ORM             | Entity Framework Core  |
| Authentication  | JWT                    |
| Styling         | Bootstrap 5            |
| Version Control | Git & GitHub           |
| Documentation   | Markdown               |

---

# 🖼 UI Preview

<p align="center">

<img src="./assets/screenshots/login.png" width="45%">
<!-- <img src="./assets/screenshots/dashboard-home.png" width="45%"> -->

</p>

<p align="center">
  <img src="./assets/screenshots/dashboard-home.png"
       alt="Dashboard"
       width="900">
</p>

<p align="center">
  <img src="./assets/screenshots/late-records.png"
       alt="Late Records"
       width="900">
</p>
<p align="center">
  <img src="./assets/screenshots/attendance.png"
       alt="Attendance"
       width="900">
</p>
<p align="center">
  <img src="./assets/screenshots/letters.png"
       alt="Letters"
       width="900">
</p>
<p align="center">
  <img src="./assets/screenshots/students.png"
       alt="Students"
       width="900">
</p>
<p align="center">
  <img src="./assets/screenshots/reports.png"
       alt="Reports"
       width="900">
</p>
<p align="center">
  <img src="./assets/screenshots/audit.png"
       alt="Audit Log"
       width="900">
</p>

---

# ⚙ Engineering Process

Unlike many portfolio projects that begin directly with implementation, AdminTrack was developed using a structured software engineering approach.

Completed engineering phases include:

- ✅ Vision Statement
- ✅ Business Analysis
- ✅ Stakeholder Analysis
- ✅ User Personas
- ✅ Functional Requirements
- ✅ Non-Functional Requirements
- ✅ System Architecture
- ✅ Data Modelling
- ✅ Service Design
- ✅ Product Backlog
- ✅ UI/UX Design
- ✅ Technical Specification
- ✅ Design System
- ✅ Master Project Specification

---

# 🧠 Challenges & Design Decisions

Some key engineering decisions included:

- Preserving paper-based classroom attendance while digitising administrative processes.
- Designing a flexible fine management system.
- Separating business logic from presentation.
- Planning for scalability without over-engineering the initial release.
- Prioritising maintainability through layered architecture and modular design.

---

# 🚀 Project Roadmap

| Phase                    | Status         |
| ------------------------ | -------------- |
| Business Analysis        | ✅ Complete    |
| Requirements Engineering | ✅ Complete    |
| System Design            | ✅ Complete    |
| UI/UX Design             | ✅ Complete    |
| Development              | 🚧 In Progress |
| Testing                  | ⏳ Planned     |
| Deployment               | ⏳ Planned     |

---

# 📫 Contact

Written By: Alexander Allotey-Bray

📧 Email: alex.bray77@gmail.com

<p align="center">

⭐ If you found this engineering case study interesting, consider giving the repository a star.

</p>
