# CMSC126\_Activity\_Unit5\_Unit6

## System Summary

**Project Title:** UPV CRS 2.0 (Course Registration System 2.0)

CRS 2.0 is a modern, scalable, and user-friendly web application designed to replace the current UPV CRS. It aims to improve the student registration experience by providing faster performance, real-time schedule conflict detection, and a clean interface.

The system will allow:

- Students to register, add/drop subjects, and view schedules  
- Faculty to manage course offerings  
- Admins to oversee enrollment, reports, and system operations

**Key Features:**

- Real-time schedule conflict checking  
- Priority-based enrollment system  
- Responsive UI for mobile and desktop  
- Secure authentication and role-based access

**Team Members:**

- \[Brent\]  
- \[Drew\]  
- \[Ethan\]  
- \[Jared\]

---

## Tech Stack

### Frontend Tools

**CSS**

---

### Backend Tools

---

### Database

**MySQL:**

- Relational database ideal for structured data (students, courses, schedules)  
- Reliable and widely used in production systems

---

### Other Tools (Optional)

- **Git & GitHub** – Version control and collaboration  
- **Figma** – UI/UX design and mockups

---

## Hosting (Platform for Hosting)

---

## Mockups

### Flowchart


A[User Opens CRS 2.0] --> B[Homepage]

```mermaid
B --> C{User Action}
C -->|Login| D[Login Form]
C -->|Browse Info| E[View Announcements / Info]

D --> F{Role Selection}
F -->|Student| G[Student Page]
F -->|Faculty| H[Faculty Dashboard]
F -->|Admin| I[Admin Dashboard]


G --> G1[View Enrolled Subjects]
G --> G2[Add / Drop Subjects]
G --> G3[View Schedule]

G2 --> J[Schedule Conflict Screen]


J --> J1[Display Selected Courses]
J --> J2[Visual Conflict Indicators]
J --> J3[Suggested Alternatives]
J --> J4[Confirm / Cancel Selection]

J4 -->|Confirm| G1
J4 -->|Cancel| G


I --> K[Admin Dashboard UI]
K --> K1[Manage Courses UI]
K --> K2[View Reports UI]
K --> K3[System Settings UI]


G --> L[Logout]
H --> L
I --> L
L --> B




### Homepage

### Student Page

### Schedule / Conflict Check Screen

### Additional Page (e.g., Admin Dashboard)
