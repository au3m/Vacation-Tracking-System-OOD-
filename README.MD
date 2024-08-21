# Vacation Tracking System (VTS) - Object Oriented Design and Analysis
VTS object oriented design focusing on detailed design and implementation including all needed diagrams and showcases.
this project developed in light of "Object-Oriented Analysis and Design with Applications - Third Edition" textbook within Eng. Ahmed Emad Mentorship program.
## Application Vision
>A Vacation Tracking System (VTS) will provide individual employees with the
capability to manage their own vacation time, sick leave, and personal time off,
without having to be an expert in company policy or the local facility’s leave
policies.
The most important goal of this system is to give individual employees the capability
and responsibility to manage this particular aspect of their employment
agreements with the company.
## System Key Features
- Implements a flexible rules-based system for validating and verifying leave
time requests
- Enables manager approval (optional)
- Provides access to requests for the previous calendar year, and allows
requests to be made up to a year and a half in the future
- Uses e-mail notification to request manager approval and notify employees
of request status changes
- Uses existing hardware and middleware
- Is implemented as an extension to the existing intranet portal system, and
uses the portal’s single-sign-on mechanisms for all authentication
- Keeps activity logs for all transactions
- Enables the HR and system administration personnel to override all actions
restricted by rules, with logging of those overrides
- Allows managers to directly award personal leave time (with system-set
limits)
- Provides a Web service interface for other internal systems to query any
given employee’s vacation request summary
- Interfaces with the HR department legacy systems to retrieve required
employee information and changes
## Use Case Model
- ### Actors:
    - Employee
    - Manager
    - Clerk
    - System Admin
- ### Use Cases:
    - Manage Time
    - Approve Request
    - Award Time
    - Edit Employee Record
    - Manage Locations
    - Manage Leave Categories
    - Override Leave Records
    - Backup System Logs
    - Top Level Use Case Model

![](https://github.com/au3m/Vacation-Tracking-System-OOD-/blob/main/assets/top%20level%20use%20case%20model.png?raw=true)
> Top Level Use Case Model
