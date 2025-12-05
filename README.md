# ADNE Clinical Management System – 2024

The ADNE Clinical Management System is an integrated desktop application designed to manage daily clinical operations, including patient records, appointments, schedules, employee management, and administrative workflows.
The system focuses on data security, efficiency, and ease of use, providing professionals with reliable tools to deliver high-quality patient care.

This project was developed by a team of five contributors as part of the PTC Project – Instituto Técnico Ricaldone (2024).

+------------------------------------------------------------+
|                       Presentation Layer                   |
|            (Windows Forms + Bunifu UI Framework)           |
+------------------------------------------------------------+
|                      Business Logic Layer                  |
|  Employee management · Appointment handling · Validation   |
+------------------------------------------------------------+
|                     Data Access Layer                      |
|           Microsoft SQL Server · XML Config Files          |
+------------------------------------------------------------+
|                       Security Layer                       |
|            AES Encryption · Email Verification             |
+------------------------------------------------------------+

# Features

## Patient Management
* Create, update, and maintain full patient profiles
* Store clinical information following the privacy laws from El Salvador such as the law 'Grow Together'
* Manage complete clinical history
* Generate electronic patient files with attachments for data portability

## Appointment & Scheduling
* Full calendar view with editing capabilities
* Appointment search and filtering
* Automatic reminders for the patients via email
* Appointment statistics and reports, helping the ADNE company grow

## Employee & Role Management
* Employee registration and data storage
* Role-based access control to keep separated the patients privacy info with the other professionals that arent administrators
* Work schedules and role permissions, 

## Administrative Tools
* System customization options
* Dark mode support
* Notification and alert settings
* PDF report generation for making more effective the patients track

# Authors

Edwin Díaz - 20220281@ricaldone.edu.sv | ed.diaz.hz@gmail.com
* User interfaces
* Patients history
* 'Remember me'
* Dashboard module
* Appointments module
* PDF generation for patients procedures
* Email reminder to patients
* Responsiveness (User Control responsiveness achieved)
* Database sub-manager

Kevin Castro - 20210033@ricaldone.edu.sv
* Employee module
* Validations
* Documentation

Jorge Pérez - 20240012@ricaldone.edu.sv | @jorPerez11
* Backend logic
* Dark mode
* Patients module
* Configuration module and user interface

Juan Rodríguez - 20240158@ricaldone.edu.sv | @sanguchitoou
* Core Backend logic
* Encryption with AES-256
* Login
* Database manager
* Documentation

Andrée Orellana - 20240012@ricaldone.edu.sv | @KeruChips
* Website for ADNE adnekids.com deployed on Netlify (No avaliable)
* Calendar module (Coauthored with Edwin Díaz)
* Testing
* Documentation
