# 🏛️ Museum Artifact Management System

> A Microsoft Access relational database application for managing museum artifacts, provenance, collections, exhibitions, storage, maintenance records, and staff assignments.

**Course:** UCCD1203 – Database Development and Applications  
**Project Type:** Academic Group Project  
**Technology:** Microsoft Access · SQL · Relational Database Design · ERD

---

## 📌 Project Overview

The **Museum Artifact Management System** is a centralized database solution designed to support museum operations by organizing and managing artifact-related information.

The system allows museum staff to manage:

- Artifact details and condition
- Artifact provenance and acquisition history
- Collections and curation records
- Exhibitions and featured artifacts
- Storage locations
- Maintenance history
- Staff responsibilities and supervision

The database was designed with structured relationships, primary and foreign keys, associative entities, and business rules to maintain data consistency and integrity.

---

## 🗂️ Database Structure

The system contains **10 relational entities**:

| Entity | Purpose |
|---|---|
| `ARTIFACT` | Stores artifact details, value, acquisition date and current condition |
| `PROVENANCE` | Records previous ownership and acquisition information |
| `COLLECTION` | Stores museum collection themes |
| `CURATION` | Connects artifacts with collections |
| `EXHIBITION` | Stores exhibition details and schedules |
| `FEATURE` | Links artifacts to exhibitions |
| `STORAGE` | Stores artifact storage locations and climate-control information |
| `REPOSITORY` | Connects artifacts with storage locations |
| `MAINTENANCE` | Records maintenance activities and history |
| `STAFF` | Stores staff information, roles and supervisory relationships |

---

## 🔗 Entity Relationship Design

The database uses:

- Primary Keys
- Foreign Keys
- Composite Keys
- One-to-One Relationships
- One-to-Many Relationships
- Many-to-Many Relationships resolved using associative entities
- Self-referencing staff supervision relationship

### ERD

> Add your ERD image here.

```markdown
![Entity Relationship Diagram](docs/erd.png)
```

---

## ✨ Key Features

### 🏺 Artifact Management

Register and maintain artifact information including:

- Artifact name
- Description
- Type
- Acquisition date
- Value
- Current condition

### 📜 Provenance Tracking

Stores historical information such as:

- Previous owner
- Previous country
- Acquisition method

### 🖼️ Collection & Exhibition Management

Supports:

- Artifact categorization into collections
- Exhibition scheduling
- Linking artifacts to multiple exhibitions
- Assignment of responsible staff

### 📦 Storage Management

Tracks:

- Storage locations
- Artifact placement
- Storage descriptions
- Climate-control information

### 🛠️ Maintenance Tracking

Records:

- Maintenance date
- Maintenance type
- Artifact involved
- Responsible staff
- Artifact condition history

### 👥 Staff Management

Stores:

- Staff information
- Staff roles
- Responsibilities
- Supervisor relationships

---

## 🔍 SQL Queries

The system includes three main queries.

### 1. Renaissance Art Collection

Retrieves artifacts associated with the **Renaissance Art** collection.

### 2. Artifact Maintenance Detail

Combines artifact, maintenance and staff information to provide a detailed view of maintenance activities.

### 3. Artifact Exhibition and Storing

Retrieves exhibition and storage information associated with museum artifacts.

---

## 📝 Forms

Three Microsoft Access forms provide a user-friendly interface for managing database records.

### Artifact Registration Form

Used to:

- Browse artifact records
- Register new artifacts
- Update artifact information

### Artifact Condition Update & Maintenance History

Used to:

- Update an artifact's current condition
- Review related maintenance records

### Exhibition Details & Management Form

Used to:

- Manage exhibitions
- View featured artifacts
- View responsible staff

---

## 📊 Reports

The database provides three formatted management reports.

| Report | Purpose |
|---|---|
| **Collection Report** | Displays artifacts grouped by collection |
| **Exhibition Report** | Displays exhibition schedules and associated artifacts |
| **Maintenance Report** | Summarizes maintenance records and artifact conditions |

---

## 🧭 Navigation

A Microsoft Access **Switchboard** provides centralized navigation to:

- Tables
- Queries
- Forms
- Reports
- Application Exit

The switchboard is configured to open automatically when the database starts.

---

## 🛠️ Technologies & Skills

- Microsoft Access
- SQL
- Relational Database Design
- Entity Relationship Diagram (ERD)
- Primary & Foreign Key Design
- Database Relationships
- Data Integrity
- Forms
- Reports
- Queries
- Microsoft Access Switchboard

---

## 📁 Repository Structure

```text
museum-artifact-management-system/
│
├── README.md
│
├── database/
│   └── Museum_Artifact_Management.accdb
│
└── docs/
    ├── Report.pdf
    ├── Report.docx
    ├── erd.png
    │
    └── screenshots/
        ├── main-switchboard.png
        ├── artifact-registration-form.png
        ├── artifact-condition-form.png
        ├── artifact-exhibition-form.png
        ├── collection-report.png
        ├── exhibition-report.png
        └── maintenance-report.png
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open:

```text
database/Museum_Artifact_Management.accdb
```

3. Launch the file using **Microsoft Access**.
4. The main switchboard will open automatically.
5. Navigate between tables, queries, forms and reports.

> Microsoft Access on Windows is recommended to preserve the forms, reports, macros and switchboard functionality.

---

## 📚 Academic Context

This project was developed as part of:

**UCCD1203 – Database Development and Applications**  
**Bachelor of Computer Science (Honours)**  
**Universiti Tunku Abdul Rahman (UTAR)**

The project demonstrates practical understanding of relational database modelling, SQL querying, database application development, data integrity and user-oriented database interfaces.

---

## ⚠️ Limitations

The current implementation is designed for small-scale Microsoft Access usage.

Possible future improvements include:

- Role-based access control
- User authentication
- Automated backup and recovery
- Improved UI/UX
- Multi-user concurrency
- Migration to MySQL / PostgreSQL
- Web-based frontend
- Data analytics dashboard

---

## 👨‍💻 Project Type

Academic group project developed by a team of four students.

---

## 📄 Documentation

Full project documentation is available in the [`docs`](docs/) directory.
