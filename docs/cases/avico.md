# AVICO NGO Management: Software Engineering capstone project

🇧🇷 [Versão em português](avico.pt-BR.md)

**Eduardo dos Santos Paim · Laravel · PostgreSQL · Docker**

[Contact](https://www.linkedin.com/in/eduardo-ds-paim/) · [Profile](https://github.com/EduardoPaim5)

## Problem and scope

A web system developed as my capstone project (TCC) to support an NGO's management of members, contributions, donations and transparency. It connects administrative routines, financial traceability and data organization.

## My role

Feature development, modeling and persistence, legacy data import, roles and permissions, audit logs, reports, tests and documentation. The reproducible environment uses Docker Compose.

## Flow chosen for evaluation

Import of fictional data → member registration → contribution → payment record → report.

This slice makes it possible to discuss data validation, duplicate handling, authorization, financial consistency and traceability without exposing members' personal information.

## Implementation decisions

- Laravel organizes validation, authorization and business rules.
- PostgreSQL holds the relational data; financial records have audit trails and protection against repeated operations.
- The import must report data problems and preserve context for review.
- Tests and documentation support preparing the flows for evaluation with users.

## Current status

The project is under development, with flows being prepared for evaluation. I do not claim operational adoption, final acceptance or productivity results without a corresponding record. The code is private; the old public link must not be used to access the repository. A demo, when prepared, uses fictional data.
