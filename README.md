# IT Support Ticketing System (osTicket)

## Overview

This project demonstrates how support tickets are handled from intake through resolution using osTicket. It focuses on the actual workflow of reviewing issues, responding to users, documenting troubleshooting steps, and tracking progress through the ticket lifecycle

---

## What This Project Demonstrates

- Ticket lifecycle management (creation, triage, resolution)
- Responding to users with clear, actionable steps
- Documenting internal troubleshooting notes
- Diagnosing common IT issues (login, printer, network, email)
- Applying SLA (Service Level Agreement) policies to tickets

---

## Tools & Technologies

- osTicket (ticketing system)
- XAMPP (Apache, MySQL, PHP)
- Localhost environment
- Web-based admin dashboard

---

## Key Scenarios Covered

This project includes multiple simulated support tickets:

- **Login Issue** – user unable to access account (password/authentication troubleshooting)
- **Printer Issue** – network printer showing offline
- **Wi-Fi Issue** – slow connectivity and network troubleshooting
- **Outlook Issue** – email sync problems

Each scenario includes:
- Customer-facing response
- Internal troubleshooting documentation
- Identified possible causes
- Next steps for resolution

---

## Support Workflow Demonstrated

1. Ticket creation and intake
2. Issue triage and categorization
3. Initial troubleshooting steps 
4. Customer communication
5. Internal documentation
6. Escalation considerations if unresolved
7. SLA assignment and tracking

---
## Project Walkthrough

### Environment Setup

#### XAMPP Running
![XAMPP Running](images/01-xampp-running.png)

#### osTicket in htdocs
![osTicket in htdocs](images/02-osticket-in-htdocs.png)

#### Installer Prerequisites Check
![Installer Prerequisites](images/03-osticket-installer-prerequisites.png)

---

### Configuration & Installation

#### Config File Missing Error
![Config File Missing](images/04-config-file-missing.png)

#### Config File Not Writable Error
![Config File Not Writable](images/05-config-file-not-writable.png)

#### Fixing Config Permissions
![Fix Config Permissions](images/06-fix-config-permissions.png)

#### Installation Form Setup
![Installation Form](images/07-installation-form.png)

#### Database Created
![Database Created](images/08-database-created.png)

#### Installation Successful
![Installation Success](images/09-installation-success.png)

---

### System Setup

#### Admin Dashboard Access
![Admin Dashboard](images/10-admin-dashboard.png)

#### Help Topics Configured
![Help Topics Configured](images/11-help-topics-configured.png)

#### Ticket Queue (Open Tickets)
![Ticket Queue](images/12-ticket-queue-open.png)

---

### Ticket Handling & Support Workflow

#### Login Issue - Customer Inquiry, Support Reply & Internal Note
![Login Internal Note](images/13-login-issues-response-internal-note.png)

---

#### Printer Issue - Customer Inquiry & Support Reply
![Printer Response](images/14-printer-ticket-response-a.png)

#### Printer Issue - Internal Note
![Printer Internal Note](images/14-printer-ticket-internal-note-b.png)

---

#### Wi-Fi Issue - Customer Inquiry & Support Reply
![WiFi Response](images/15-wifi-ticket-response-a.png)

#### Wi-Fi Issue - Internal Note
![WiFi Internal Note](images/15-wifi-ticket-internal-note-b.png)

---

#### Outlook Issue - Customer Inquiry & Support Reply
![Outlook Response](images/16-outlook-ticket-response-a.png)

#### Outlook Issue - Internal Note
![Outlook Internal Note](images/16-outlook-ticket-internal-note-b.png)

---

### SLA Configuration

#### SLA Policy Configured
![SLA Configured](images/17-sla-configured.png)

#### Ticket with SLA Applied
![Ticket with SLA](images/18-ticket-with-sla.png)
