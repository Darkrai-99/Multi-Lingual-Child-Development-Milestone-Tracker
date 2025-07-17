# Multi-Lingual Child Development Milestone Tracker

This is a web-based platform designed to track developmental milestones in children up to six years old. The project supports parents, ASHA and ICDS workers in monitoring child growth, identifying delays, and connecting with medical professionals for timely intervention. It includes multilingual support and is built for accessibility in rural and underserved regions.

---

## Features

- Periodic data collection for child growth based on WHO guidelines
- Alerts for developmental delays or risk flags
- Real-time video consultations with doctors via Jitsi Meet
- Multilingual interface for broader reach
- Disability detection and referral to support services
- Regional analytics and hotspot detection
- Support for therapies, surgeries, and school enrolment

---

## Purpose

This system aims to:

- Enhance child health surveillance in underserved areas
- Enable early detection of developmental disabilities
- Provide timely medical guidance and access to relevant schemes
- Empower parents and field workers with reliable digital tools
- Support data-based planning and targeted interventions

---

## Tech Stack

| Layer             | Technology Used                          |
|------------------|-------------------------------------------|
| Frontend         | React.js, Tailwind CSS, HTML, JavaScript  |
| Backend          | Node.js, Express.js                       |
| Database         | MongoDB, MySQL                            |
| Video Calls      | Jitsi Meet API                            |
| Hosting          | Render (Frontend), AWS EC2 (Backend)      |
| Testing          | Mocha (Unit), Cypress (E2E)               |
| API & Tools      | Axios, Postman                            |

---

## System Architecture

- **User Interface Layer**: Web app for parents, ASHA/ICDS workers, and administrators
- **Application Layer**: Notification logic, data analysis, and integration
- **Data Layer**: MongoDB and MySQL for storing user profiles and health data
- **Integration Layer**: APIs for video consultations and analytics

---

## User Roles

- Parents / Guardians
- ASHA / ICDS Workers
- System Administrators
- Medical Professionals

---

## Input Data

- Child’s demographic information (name, age, gender, region, etc.)
- Growth metrics (height, weight, cognitive and motor development)
- ASHA/ICDS field entries
- Medical records for flagged cases
- Disability-specific data
- Video consultation scheduling

---

## Output Data

- Notifications for missed milestones or delays
- Regional analytics for disability trends
- Individual child development reports
- Medical consultation summaries
- Therapy, surgery, and school enrolment updates
- Government scheme notifications

---

## Installation (Development Mode)

### 1. Clone the Repository

```bash
git clone https://github.com/Darkrai-99/Multi-Lingual-Child-Development-Milestone-Tracker.git
cd Multi-Lingual-Child-Development-Milestone-Tracker
