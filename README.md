<h1 align="center">DONATE BLOOD</h1>
<p align="center">WebApplication Requirements (High level)</p>

<u> **DONATE BLOOD** </u> is a robust and comprehensive donation management system designed
to streamline communication and appointment processes between recipients, donars,
and administrators. The system incorporates cutting-edge technologies such as
NodeJS, Express, Prisma, WEB RTC (via Agora.io), and PostgreSQL for efficient and
secure data management.

<!-- # [CLIENT SIDE]() -->
<!-- ## [SERVER SIDE](https://github.com/itskawsarjamil/donate_blood_backend) -->

| CLIENT SIDE                                              | [SERVER SIDE](https://github.com/itskawsarjamil/donate_blood_backend) |
| :----:                                                    |    :----:                                                             |


# Project Overview

## 1. Technologies

- **NodeJS and Express**: Used for server-side application development.
- **WEBRTC (Agora.io)**: Third-party service for real-time communication between donars and recipients.
- **Prisma**: ORM (Object-Relational Mapping) tool for database management.
- **PostgreSQL**: Database management system.
<!-- - **Next.js**: A React framework for building applications. -->

---

## 2. User Roles and Functionalities

### 2.1 Admin

#### Account Management

- Create and manage donars accounts.

#### Appointment Management

- Create schedule slots.

#### Access to Information

- View metadata.
- Manage donars appointment slots (change appointment status).
- View appointment history and details.
- Access and manage donars profiles.

---

### 2.2 Donars

#### Appointment Management

- View upcoming appointments.
- Set appointment slots.
- Take appointments.

#### recipient Profile

- Access recipient profiles and medical history.
- View uploaded diagnostic test reports of recipients.
- View previous prescriptions (if any).

<!-- #### Prescription Management

- Generate prescriptions for recipients during and after consultations.
- Send prescriptions to recipients through email via the system.
- Attach additional medical notes and instructions to prescriptions. -->

---

### 2.3 recipient

#### Account Management

- Register a new account during the first visit.
- Leverage features for password recovery and account security.

#### Appointment Booking

- Schedule appointments with available time slots.
- Book appointments with specific donars.

#### Medical Record Management

- Manage personal profile data.
- Maintain medical history.
- Upload diagnostic test reports.

<!-- #### Prescription Access

- Access and view prescriptions.
- Receive prescriptions through the platform. -->

#### Payment and Confirmation

- Pay transport fees when booking appointments.
- Receive an email confirmation with an invoice after successful payment.
- Appointments are confirmed only (if transport fees needed) after payment.
- If payment is not made within 30 minutes of booking, the booking will be automatically canceled.

#### Reviews

- Provide reviews with ratings for donars.
- Include a comment section for additional feedback.
- View and manage previously submitted reviews.

---

## 3. System Features

- Real-time communication through WebRTC.
- Secure user authentication and authorization.
- Seamless appointment scheduling and management.
- Comprehensive recipient profiles and medical records.
- Integrated secure payment system for transport or something.
- Donars can generate detailed feedback during and after donation.
- Automated email notifications for:
  - Appointment confirmations

---

## 4. Single-Page Application (SPA)

- **Landing Page**: Provides information about the DONATE BLOOD system.
- **Donar Profile**: Displays detailed information about donars.

<br><br/>
<br><br/>


| **Please note that the content of this requirement document is presented at a high level without specific references.The requirements will be subject to change based on the facility and project needs** |
|    :----:   |
