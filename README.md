# Garuda Fitness Zone | Gym Management System

**A modern digital platform for smarter gym management.**

Garuda Fitness Zone is a web-based gym management platform designed to simplify daily operations, improve membership administration, and provide members with a convenient way to manage their fitness journey.

The platform brings membership records, fee tracking, attendance, fitness progress, and administrative controls together in one place. Its responsive interface is designed to work across desktop computers, tablets, and mobile devices.

---

## Overview

Managing a gym involves more than training members. Administrators need to keep track of memberships, payments, attendance, renewals, and member records while ensuring that members have a smooth experience.

Garuda Fitness Zone addresses these everyday operational needs through a centralized web application.

The system provides dedicated administrative and member experiences, database-backed records, cloud-based image storage, and support for membership-related notifications.

## Features

### 1. Member Management
- Register and manage gym members.
- Maintain individual member profiles and membership information.
- Search for members and filter records.
- Track membership status and expiry dates.
- Update relevant member information through administrative controls.

### 2. Membership Management
- Maintain membership details and renewal information.
- Monitor upcoming membership expirations.
- Identify expired memberships.
- Track payment status alongside membership records.
- Help administrators manage renewals and follow up with members.

### 3. Payment and Fee Tracking
- Maintain paid and unpaid membership records.
- Identify members with pending dues.
- Filter members by payment status.
- Allow administrators to update payment status manually.
- Keep membership payment information organized for daily operations.

*Payment status management is separate from online payment processing; payment gateway functionality depends on the configured integrations.*

### 4. Attendance Management
- Provide members with an attendance calendar.
- Allow attendance records to be monitored through the application.
- Help administrators and members keep track of attendance activity.
- Support membership-related access restrictions where configured.

### 5. Fitness Progress Tracking
- Maintain member weight records.
- Monitor changes in weight over time.
- Visually distinguish weight gain from weight loss.
- Give members a convenient way to follow their fitness progress.

### 6. Member Dashboard
Members can access their personal gym information through their account, including supported membership details, payment status, attendance information, and fitness progress.

The dashboard brings important information together without requiring members to rely entirely on manual records.

### 7. Administrative Dashboard
The administrative interface centralizes day-to-day gym operations.

Administrators can manage member records, review membership expiry, monitor outstanding payments, update payment status, and maintain other supported gym information from one place.

### 8. Automated Notifications
The notification workflow is designed to help reduce manual follow-ups and improve communication with members.

Planned notification events include:

- **Upcoming expiry:** Remind members three days before their membership expires.
- **Membership expiry:** Notify members when their membership expires.
- **Pending dues:** Notify members when their payment remains outstanding.
- **Welcome messages:** Send account details when a new member is registered, where configured.

WhatsApp Business messaging through Meta requires valid API credentials, approved message templates where applicable, and a correctly configured backend integration. Actual delivery depends on the integration being enabled and successfully tested.

### 9. Cloud-Based Image Storage
Cloudinary integration supports persistent image storage for supported application features.

This allows uploaded images to remain available independently of temporary application storage, subject to the configured upload and retrieval workflows.

### 10. Responsive User Interface
- Designed for desktop, tablet, and mobile screens.
- Organized layouts for administrative and member workflows.
- Clear membership and payment status indicators.
- Search and filtering for easier record management.
- A consistent interface focused on usability.

---

## How the System Works

### Administrator Workflow

**Step 1 — Sign in**

The administrator accesses the management dashboard using authorized credentials.

**Step 2 — Register a member**

The administrator creates a member record and enters the required profile and membership information.

**Step 3 — Manage membership**

The system stores membership details and expiry information for subsequent tracking.

**Step 4 — Track payments**

The administrator reviews fee records, identifies pending dues, and updates payment status when payment is confirmed.

**Step 5 — Monitor attendance and progress**

Available attendance records and member fitness information can be reviewed through the application's supported interfaces.

**Step 6 — Handle renewals and notifications**

Membership expiry and outstanding dues provide the basis for follow-up notifications. Automated messages require the corresponding notification integration to be configured and verified.

### Member Workflow

**Step 1 — Access the account**

The member signs in using the account credentials provided through the gym's registration process.

**Step 2 — Review membership**

The member views available personal membership information and expiry details.

**Step 3 — Check payment status**

The member can review supported payment and membership status information.

**Step 4 — Monitor attendance**

The member uses the attendance calendar to view available attendance information.

**Step 5 — Follow fitness progress**

The member reviews recorded weight information to monitor changes over time.

**Step 6 — Respond to renewal reminders**

Where messaging is enabled, the member can receive relevant membership or payment notifications.

---

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML, CSS and JavaScript | User interface and client-side functionality |
| Node.js | Server-side JavaScript runtime |
| Express.js | Backend routes and application services |
| MongoDB | Database for application records |
| MongoDB Atlas | Cloud-hosted database deployment |
| Cloudinary | Cloud image storage |
| Meta WhatsApp Business API | Membership messaging integration, subject to configuration |
| Render | Application hosting and deployment |

The exact technologies used by individual features depend on the deployed application version and its configuration.

## Application Architecture

The application follows a client-server architecture.

1. **Frontend:** Displays the website, dashboards, forms, calendars, and member information.
2. **Backend:** Processes supported requests, applies application logic, and manages communication with connected services.
3. **Database:** Stores persistent application records in MongoDB.
4. **Cloud storage:** Handles supported image uploads and retrieval through Cloudinary.
5. **External integrations:** Provide messaging and other connected services when configured.

This separation helps organize the application into maintainable components.

## Security and Reliability

The platform is intended to support controlled administrative access and reliable storage of gym records.

Production deployment should include:

- Server-side authentication and authorization.
- Appropriate access restrictions for administrative operations.
- Secure environment variable management.
- Protected database credentials and API tokens.
- Server-side validation of user input.
- Appropriate error handling and logging.
- Testing of membership, payment, and notification workflows.

Security and production readiness depend on the actual implementation and deployment configuration.

## Deployment

The application is designed for web hosting, with Render and MongoDB Atlas supporting the deployment architecture.

A typical deployment workflow involves:

1. Preparing the application and its dependencies.
2. Configuring production environment variables.
3. Connecting the application to MongoDB Atlas.
4. Configuring Cloudinary credentials.
5. Setting up any required messaging API credentials.
6. Deploying the application to the hosting environment.
7. Testing login, member management, payments, attendance, and notification workflows.

Production credentials must be configured securely and must never be committed to a public repository.

## Project Goals

Garuda Fitness Zone aims to make gym administration more organized by reducing dependence on disconnected records and repetitive manual tasks.

The project focuses on:

- Simplifying daily gym operations.
- Improving membership and renewal tracking.
- Making payment status easier to monitor.
- Providing convenient member access to personal information.
- Supporting fitness progress monitoring.
- Creating a foundation for further automation and integration.

## Future Improvements

Potential areas for continued development include:

- Expanded membership and payment reports.
- Improved attendance analytics.
- More detailed fitness progress charts.
- Enhanced notification delivery monitoring.
- Payment gateway integration.
- Additional administrative reporting and audit history.
- Biometric attendance and access-control integration.

These items represent potential enhancements and should not be interpreted as currently implemented features.

---

## Project Information

**Project:** Garuda Fitness Zone  
**Category:** Gym Management System  
**Platform:** Web Application  
**Backend:** Node.js and Express.js  
**Database:** MongoDB  
**Image Storage:** Cloudinary  
**Deployment:** Render

Developed to make gym management simpler, more organized, and more convenient for both administrators and members.

**Garuda Fitness Zone — Train Better. Manage Smarter.**
