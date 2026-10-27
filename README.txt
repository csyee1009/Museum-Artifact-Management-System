# Museum Artifact Management System

A relational database application developed using Microsoft Access to support the management of museum artifacts, collections, provenance, storage, exhibitions, maintenance records, and staff.

This project was developed as a group project for **UCCD1203 – Database Development and Applications** at Universiti Tunku Abdul Rahman (UTAR).

## Overview

The Museum Artifact Management System provides a centralized database for museum staff to store, retrieve, update, and manage artifact-related information.

The system supports artifact registration, provenance tracking, collection categorization, storage management, exhibition planning, maintenance history, artifact condition monitoring, and staff assignment.

## Database Design

The database consists of 10 main entities:

- Artifact
- Provenance
- Collection
- Curation
- Maintenance
- Staff
- Exhibition
- Feature
- Storage
- Repository

Primary and foreign key relationships are used to maintain referential integrity, while associative entities resolve relationships between artifacts, collections, exhibitions, storage locations, and maintenance activities.

## Key Features

### Artifact Management

Stores artifact information including name, description, type, acquisition date, value, and current condition.

### Provenance Tracking

Maintains information about previous ownership, country of origin, and acquisition method.

### Collection Management

Organizes artifacts into museum collections and records their curation information.

### Exhibition Management

Tracks exhibitions, participating artifacts, exhibition schedules, and responsible staff.

### Storage Management

Tracks artifact storage locations, repository placement, and climate-control information.

### Maintenance Tracking

Maintains artifact maintenance history including maintenance type, date, responsible staff, and artifact condition.

### Staff Management

Stores staff information, roles, responsibilities, and supervisory relationships.

## Queries

The system includes several SQL queries for retrieving and analysing museum information.

**Renaissance Art Collection**

Retrieves artifacts associated with the Renaissance Art collection for collection review and exhibition planning.

**Artifact Maintenance Detail**

Combines artifact, maintenance, and staff information to provide a complete view of maintenance activities and responsibilities.

**Artifact Exhibition and Storing**

Provides an overview of artifact exhibition status and storage information.

## Forms

The application provides interactive Microsoft Access forms for easier database operation.

**Artifact Registration Form**

Allows users to browse existing artifact records and register new artifacts.

**Update Artifact Condition Form**

Allows artifact condition information to be updated while displaying the associated maintenance history.

**Artifact Exhibition Form**

Provides an interface for viewing and managing exhibitions, artifacts, and responsible staff.

## Reports

The system contains formatted reports for operational and management use.

**Collection Report**

Groups museum artifacts according to their respective collections.

**Exhibition Report**

Summarizes exhibition schedules and associated artifacts.

**Maintenance Report**

Summarizes artifact maintenance activities, maintenance dates, conditions, and maintenance types.

## Navigation

A Microsoft Access switchboard provides a centralized navigation interface for accessing forms, queries, tables, reports, and application controls.

## Technologies

- Microsoft Access
- SQL
- Relational Database Design
- Entity Relationship Diagram (ERD)
- Database Forms and Reports
- Access Switchboard and Macros

## Running the Project

1. Clone or download this repository.
2. Open `database/Museum_Artifact_Management.accdb` using Microsoft Access.
3. The main switchboard provides access to the application's forms, queries, tables, and reports.

Microsoft Access for Windows is recommended to preserve the application's forms, reports, macros, and switchboard functionality.

## Academic Context

This project was developed as a four-member academic group project for **UCCD1203 – Database Development and Applications**.

The project demonstrates relational database modelling, entity-relationship design, SQL querying, data integrity, database application development, and user-oriented database interfaces.

## Known Limitations

The current Microsoft Access implementation is intended for small-scale use and has limited scalability for large datasets or concurrent users. Future improvements could include role-based access control, automated backup and recovery, improved user-interface design, database migration to a server-based DBMS, and analytics or visualization capabilities.