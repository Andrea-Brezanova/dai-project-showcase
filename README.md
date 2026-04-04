# dai-project-showcase: Internal Procurement Data Management Application
This project was completed during my internship for a client. The codebase is private; the README highlights my contributions, technologies used, and project features.

# Project Overview

This project is a portfolio-safe summary of a web-based internal application I designed and implemented during my vocational training. The goal was to replace fragmented, manual data handling with a centralized system for managing procurement-related records in a more structured, maintainable, and scalable way.

The application was built with Python, Django, and MariaDB and focused on the core workflow of creating and storing structured records through a database-backed web interface.

# Problem

The original workflow relied on outdated non-relational database and repeated manual data entry. This created unnecessary administrative effort, made data harder to maintain consistently, and reduced transparency across related records.

The project addressed this by designing a central application that:

reduces duplicate data entry,
improves data consistency,
supports structured record creation,
and creates a better technical foundation for future workflow expansion.

# My Role

I was responsible for the technical design and implementation of the solution, especially in these areas:

analyzing the business workflow and translating it into a technical structure,
designing the relational database model,
implementing the schema in Django models,
building form-based record creation flows,
connecting the application to MariaDB,
and developing the backend and frontend structure for the core use case.
Architecture and Tech Stack

The application was implemented as a server-rendered web application using Django.

# Technologies used:

Python
Django
MariaDB
HTML / CSS
Django ORM
Git

The architecture followed a clear separation between:

data model layer for database structure,
business logic layer for validation and request handling,
presentation layer for templates and user interaction.

This made the project easier to maintain, extend, and test.

# Database Design

A major part of the project was designing the relational database structure.

I began by identifying the key entities involved in the workflow and modeling them in a normalized way so that reusable information could be stored once and referenced where needed. The design focused on reducing redundancy while keeping the structure flexible enough for future development.

Design goals
reduce duplicated data,
separate reusable reference data from transactional records,
model clear relationships between entities,
support maintainability and future expansion,
and align the schema with real workflow requirements.
Implementation approach

The central record model was linked to multiple reference tables using foreign keys. This allowed the application to store structured relationships instead of repeating the same values in multiple places.

I also worked on modeling related lookup data in a way that supported dropdown-based input in forms. In one case, I added an additional classification field to support more specific selection logic for locations/organizational units while keeping the data model structured and reusable.

# Django Implementation

After designing the schema, I implemented the application in Django.

What I built
Django models representing the relational data structure
form classes for user input and validation
view logic for creating and displaying records
template-based pages for data entry and record detail views
integration with MariaDB through Django ORM

The project helped me understand how to move from a conceptual data model to a working application flow.

# Form and Workflow Logic

A key implemented use case was the creation of a new record through a web form.

The workflow included:

displaying a structured input form,
validating required fields and data formats,
handling related database objects,
saving valid data to the database,
and redirecting the user to a detail page after successful creation.

I also implemented custom form behavior for selected fields so that the application could handle both predefined values and user-entered values in a controlled way.

# User Interface

The frontend was implemented with Django templates and structured as a classic internal web application with navigation, forms, status messages, and detail views.

The interface design focused on:

clarity,
structured data entry,
readable detail pages,
and practical usability for internal users.
What I Learned

This project significantly strengthened my skills in:

relational database modeling,
Django model design,
form handling and validation,
backend workflow implementation,
template-based frontend development,
and translating business requirements into maintainable software.

It also deepened my understanding of how backend logic, database design, and user workflows work together in real business applications.

# Outcome

The result was a working internal web application prototype that demonstrated how a fragmented administrative workflow could be improved through a centralized, database-driven solution.

From a development perspective, this project gave me hands-on experience with full-stack web development, database design, and workflow automation in a real-world environment.

# Portfolio Note

This README is intentionally written as a sanitized public summary. It focuses on the technical design, implementation approach, and learning outcomes of the project without disclosing confidential internal details, sensitive operational information, or organization-specific data.

# Project Preview

(Add screenshots)
--> see related repository "dai-demo"

# Contact

For more information or to discuss the project:

LinkedIn: https://www.linkedin.com/in/andrea-brezanova
