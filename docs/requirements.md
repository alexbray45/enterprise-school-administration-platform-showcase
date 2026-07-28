# 📋 Requirements Engineering

## Overview

Requirements engineering is a critical phase of the software development lifecycle that defines what a system should accomplish and the constraints under which it must operate.

For AdminTrack, requirements were gathered through an analysis of the existing administrative attendance process and discussions around the operational needs of the institution.

The requirements documented in this case study represent a high-level overview of the platform's capabilities and are intentionally limited to preserve implementation details.

---

# Functional Requirements

The platform is designed to support the following core business functions.

| Module              | Description                                                    |
| ------------------- | -------------------------------------------------------------- |
| Authentication      | Secure user authentication and role-based access control.      |
| Student Management  | Manage student information used for attendance administration. |
| Absence Management  | Record and manage student absences.                            |
| Lateness Management | Record student lateness and maintain attendance history.       |
| Fine Management     | Calculate and manage lateness fines.                           |
| Reporting           | Generate attendance summaries and management reports.          |
| Dashboard           | Provide administrators with operational insights.              |
| Audit Logging       | Maintain a record of significant administrative activities.    |

---

# User Roles

The system supports multiple user roles with responsibilities appropriate to their administrative functions.

| Role                     | Primary Responsibilities                                                            |
| ------------------------ | ----------------------------------------------------------------------------------- |
| Attendance Administrator | Daily attendance administration, lateness recording, fine management and reporting. |
| Assistant Vice Principal | Oversight of attendance records and absence management.                             |
| Principal                | Review reports and monitor attendance trends.                                       |
| System Administrator     | User management, permissions and system administration.                             |

---

# Functional Scope

The platform provides capabilities including:

- Secure authentication
- Student record management
- Attendance administration
- Absence recording
- Lateness tracking
- Automatic fine calculation
- Administrative reporting
- Dashboard analytics
- Audit logging

---

# Non-Functional Requirements

In addition to business functionality, the system has been designed to satisfy key quality attributes.

| Category        | Requirement                                                                  |
| --------------- | ---------------------------------------------------------------------------- |
| Performance     | Provide responsive user interactions and efficient data retrieval.           |
| Security        | Protect data through authentication, authorisation and secure communication. |
| Reliability     | Ensure consistent system operation and data integrity.                       |
| Scalability     | Support future growth in users and institutional requirements.               |
| Maintainability | Promote modular development and ease of future enhancements.                 |
| Usability       | Provide an intuitive administrative user experience.                         |

---

# Assumptions

The following assumptions were made during requirements analysis.

- Classroom attendance continues to be recorded using paper registers.
- Student records are imported from existing institutional data.
- The system is intended for internal administrative use.
- Users have appropriate permissions based on their organisational roles.

---

# Constraints

The project operates within several constraints.

- Existing classroom attendance procedures remain unchanged.
- Sensitive institutional data must be protected.
- The platform should integrate smoothly into existing administrative workflows.
- The initial release focuses on attendance administration only.

---

# Success Criteria

The solution is expected to:

- Reduce manual administrative effort.
- Improve attendance record accuracy.
- Simplify lateness tracking.
- Improve reporting efficiency.
- Support informed decision-making.
- Provide a scalable foundation for future enhancements.

---

# Requirements Engineering Approach

Rather than moving directly into implementation, the project followed a structured requirements engineering process consisting of:

1. Business analysis
2. Stakeholder identification
3. Problem definition
4. Scope definition
5. Functional requirement identification
6. Non-functional requirement analysis
7. Validation of business needs

This process ensured that the proposed solution addressed genuine operational challenges before architectural and technical design activities commenced.

---

# Conclusion

The requirements defined for AdminTrack establish the foundation for the system's architecture, user experience, and implementation.

By clearly identifying business objectives, user needs, system capabilities and quality attributes, the project provides a well-defined roadmap for developing a maintainable and scalable school administration platform.
