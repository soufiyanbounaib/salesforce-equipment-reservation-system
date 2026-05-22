# Equipment Reservation Management System | Salesforce Admin Project

##  Project Overview

The Equipment Reservation Management System is a Salesforce-based application designed to help organizations manage shared equipment reservations efficiently.

The project focuses on reducing scheduling conflicts, improving approval workflows, automating notifications, and providing operational visibility through reports and dashboards.

This project was built as a hands-on Salesforce Admin portfolio project to demonstrate practical experience with Salesforce automation, security configuration, reporting, and Lightning App customization.

---

#  Key Features

##  Reservation Management
- Employees can create and manage equipment reservations.
- Reservation records include scheduling details, equipment information, and reservation purpose.

##  Approval Workflow
- High-value equipment reservations require manager approval.
- Approval processes automatically route requests to the employee’s manager.

##  Conflict Detection
- Record-triggered Flow prevents overlapping reservations for the same equipment and time period.

##  Scheduled Notifications
- Scheduled Flow sends reminder notifications before reservation start dates.

##  Security Model
- Organization-Wide Defaults (OWD)
- Role Hierarchy
- Permission Sets
- Profile-based access control

##  Reporting & Dashboards
- Pending Reservations Report
- Equipment Usage Report
- Approval Status Overview
- Upcoming Reservations Dashboard

##  Lightning Experience Customization
- Custom Lightning App
- Lightning Record Pages
- List Views
- Compact Layouts

---

#  Salesforce Features Used

- Custom Objects & Relationships
- Record-Triggered Flows
- Scheduled Flows
- Approval Processes
- Validation Rules
- Permission Sets
- Role Hierarchy
- Reports & Dashboards
- Lightning App Builder
- Dynamic Lightning Pages

---

#  Data Model

## Custom Objects
- Equipment
- Reservation

## Main Relationships
- Reservation → Equipment
- Reservation → Employee (User)

---

#  Security Configuration

The project includes a role-based security architecture:

- Employees can manage their own reservations.
- Managers can review and approve team reservations.
- Record visibility is controlled using OWD and Role Hierarchy.
- Permission Sets provide additional access where necessary.

---

#  Dashboard & Reports

The dashboard provides operational visibility into:

- Pending approval requests
- Equipment usage trends
- Reservation approval statistics
- Upcoming approved reservations

---

#  Automation Highlights

## Record-Triggered Flow
- Detects conflicting reservations automatically.

## Scheduled Flow
- Sends reservation reminder notifications.

## Approval Process
- Routes high-value reservations to managers for approval.

---

#  Business Value

This application demonstrates how Salesforce can be used to streamline internal operational processes through automation, approval workflows, security configuration, and reporting.

The solution helps:
- reduce scheduling conflicts
- improve reservation visibility
- automate manual processes
- support approval governance

---

#  Screenshots

## Dashboard


## Reservation Record Page


## Approval Process


## Flow Automation


---

#  Future Improvements

Possible future enhancements include:
- Email notifications
- Calendar integration
- Mobile optimization
- Asset availability forecasting
- Advanced analytics


