# OLX Claim AI

A full-stack business and event platform developed as a team project, combining backend development, AWS deployment, automated email workflows, administrative content management, and password-protected event content.

The project evolved through two major versions:

* **Version 1:** Pre-event business website with automated email workflows.
* **Version 2:** Event platform with an administrative panel, media management, and protected event content.

---

## My Role

**Backend Developer & Deployment**

I was primarily responsible for the backend, cloud deployment, email automation, and administrative functionality.

### Key Contributions

* Backend development
* AWS EC2 deployment
* Amazon SES integration
* Mailgun integration
* Email automation
* Form-processing workflows
* Administrative panel development
* Event content management
* Video and gallery management
* Password-protected content
* Session-based access control
* Backend security
* Deployment and troubleshooting

---

# Version 1 — Pre-Event Website

The first version was developed as the business website before the event.

### Main Features

* Business website
* Dynamic forms
* Backend form processing
* Automated email responses
* Administrator email notifications
* Email template management
* Recipient management
* AWS deployment

### Email Automation

Two major email workflows were implemented.

#### Form-Based Auto Reply

When a visitor submits a form, the backend processes the submission and sends:

```text
User
  ↓
Website Form
  ↓
Backend
  ↓
Form Validation
  ↓
Email Processing
  ├──→ User Auto-Reply
  └──→ Admin Notification
```

The auto-reply can be customized according to the form submitted.

#### Template-Based Admin Emails

Administrators can select an email template and send emails to recipients managed within the system.

```text
Admin
  ↓
Admin Panel
  ↓
Select Template
  ↓
Select Recipients
  ↓
Backend
  ↓
Email Service
  ↓
Recipients
```

---

# Version 2 — Event Platform

The second version extended the project into an event-content platform.

The new platform provides functionality for displaying and managing:

* Event videos
* Event galleries
* Photos
* Event-related content

A dedicated administrative panel was developed to manage this content.

---

## Admin Panel

The administrator can manage event content through the backend rather than modifying the website directly.

The system provides management functionality for:

* Videos
* Galleries
* Photos
* Event content
* Protected media

---

## Password-Protected Event Content

Specific event video pages can be protected with a password.

The access flow is:

```text
Visitor
  ↓
Protected Video Page
  ↓
Password Required
  ↓
Password Validation
  ↓
Access Granted
  ↓
Protected Video
```

The administrator can provide the password to authorized individuals.

After successful authentication, the access state is maintained during the active session, allowing the user to navigate through the website and return to the protected content without repeatedly entering the password.

---

# Website Integration

The second version also maintains access to the previous website.

The navigation includes an **2026 Edition** section that links users to the previous pre-event website.

```text
New Event Platform
        │
        ├── Home
        ├── About
        ├── Contact
        └── 2026 Edition
                  │
                  ↓
        Previous Website
              Version 1
```

This allowed the previous website and the new event platform to coexist as part of the overall project.

---

# Technology Stack

### Backend

* PHP
* Server-side application development
* Email automation
* Session-based access control

### Cloud & Deployment

* AWS EC2
* Linux server environment
* Amazon SES
* Mailgun

### Frontend

* HTML
* CSS
* JavaScript

### Administration

* Custom Admin Panel
* Content Management
* Media Management
* Access-Controlled Content

---

# High-Level Architecture

```text
                         USERS
                           │
                           ▼
                    Web Application
                           │
                           ▼
                        Backend
                      /         \
                     /           \
                    ▼             ▼
               Database      Email Services
                              /         \
                             ▼           ▼
                        Amazon SES    Mailgun


                     ADMINISTRATOR
                           │
                           ▼
                       Admin Panel
                       /         \
                      ▼           ▼
                 Content       Protected
                 Management      Media
                                   │
                                   ▼
                            Password Validation
```

---

# Team Structure

The project was developed collaboratively by four team members.

### Team Member 1

**UI/UX Design**

* Created the Figma design.

### Team Member 2

**Frontend Development**

* Implemented the frontend according to the design.

### Team Member 3

**Client Communication & Requirements**

* Communicated with the client.
* Gathered and clarified project requirements.

### My Role

**Backend Development & Deployment**

* Backend development
* AWS deployment
* Email automation
* Amazon SES integration
* Mailgun integration
* Admin panel
* Event content management
* Protected media access

---

# Project Evolution

```text
VERSION 1
Pre-Event Business Website
        │
        ├── Business Pages
        ├── Forms
        ├── Email Automation
        ├── Admin Email Workflows
        └── AWS Deployment
        │
        ▼
VERSION 2
Event Platform
        │
        ├── Admin Panel
        ├── Event Videos
        ├── Galleries
        ├── Photos
        ├── Protected Content
        └── Version 1 Integration
```

---

# Key Engineering Areas

This project provided practical experience in:

* Backend development
* Cloud deployment
* AWS EC2
* Transactional email systems
* Email automation
* Third-party service integration
* Administrative systems
* Access control
* Session management
* Media management
* Client-oriented development
* Team collaboration
* Production deployment
* Troubleshooting

---

# Developer Contribution

My contribution focused on the backend and deployment side of the project, including application logic, AWS infrastructure, email automation, administrative functionality, and controlled access to event content.

---

## Source Code

The production source code is maintained in a private repository because this project was developed for a client.

Source code may be provided for technical review to authorized recruiters, clients, or collaborators upon request.

Production credentials, API keys, private client information, and sensitive configuration are not included in this repository.

## Screenshots


## Project Link
www.olxclaim.com

