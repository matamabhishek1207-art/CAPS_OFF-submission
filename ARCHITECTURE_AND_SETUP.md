#ARCHITECTURE
## 1. Frontend Architecture

The application uses a multi-page dashboard structure.

Main pages:

• index.html → Landing page and role selection  
• student-dashboard.html → Student portal  
• faculty-dashboard.html → Faculty portal  
• admin-dashboard.html → Admin portal  
• authority-dashboard.html → Authority portal  

Each dashboard is isolated and role-specific.  
This improves scalability and allows backend integration later.
---
## 2. Design System

All dashboards share a unified UI design:

• Dark-themed academic workspace  
• Glassmorphism UI components  
• Sidebar navigation layout  
• Card-based dashboard widgets  
• Dynamic section switching using JavaScript  

The dashboards behave like a single-page application using section toggling.

---
## 3. Dashboard Modules

### Student Dashboard

Modules included:
• Dashboard
• Enrolled Courses  
• Attendance Tracking  
• Assignments & Submissions  
• Announcements  
• Academic Tracker  
• Vault of Knowledge  
• Calendar  
• Research & Internships  
• Grievance Portal  

This dashboard represents the student academic workflow.

### Faculty Dashboard

Faculty features:
• Course management  
• Vault of Knowledge 
• Upload notes and resources  
• Create assignments  
• View student submissions  
• Post announcements  
• TA Recruitment

This dashboard simulates instructor tools.

---

### Admin Dashboard

Admin features:
• User management  
• Faculty monitoring  
• Global search  
• System statistics  
• Approvals and management tools  

Admin acts as the system controller.

---

### Authority Dashboard

Authority features:
• Institutional analytics  
• User approvals  
• Reports and statistics  
• System oversight  

Authority represents executive-level access.

---
## 4. Navigation Flow

Navigation uses sidebar-driven architecture.

User Flow:
Login → Dashboard → Sidebar → Module Section

Sections load dynamically without full page refresh.

---

## 6. Backend Architecture (Conceptual)

The system is designed for backend integration.

Backend responsibilities:
• Authentication & role management  
• Database storage  
• Attendance tracking  
• Assignment handling  
• Announcements system  
• Grievance management  

Recommended backend stack:
• Node.js + Express  
• MongoDB / Firebase  
• REST API architecture  

---
## 7. Setup Guide

### Requirements

Install:
• Git  
• Web Browser (Chrome recommended)  
Optional: Node.js for backend

---

### Run Frontend Locally

1. Clone the repository

git clone <repo-link>

2. Open the project folder

3. Run the project  
Open index.html in the browser

The project runs without build tools.

---

## 7. Setup Guide

### Requirements

Install:
• Git  
• Web Browser (Chrome recommended)  
Optional: Node.js for backend

---

### Run Frontend Locally

1. Clone the repository

git clone <repo-link>

2. Open the project folder

3. Run the project  
Open index.html in the browser

The project runs without build tools.

---
### 9. Why Firebase Was Chosen

Firebase was selected because it provides:

• Serverless backend architecture  
• Real-time database capabilities  
• Built-in authentication  
• Easy deployment and scalability  
• Fast development for hackathon timeline

---

### Backend Architecture Summary

Frontend Dashboards → Firebase Authentication → Firestore Database → Firebase Storage

This architecture enables a scalable full-stack academic portal.


