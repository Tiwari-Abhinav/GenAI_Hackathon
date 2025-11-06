Smart Campus Platform 🎓

A modern, AI-powered campus management platform inspired by Teachmint's clean and professional design. Built with React, TypeScript, Tailwind CSS, and Firebase, featuring face recognition attendance and productivity insights.



🚀 Features

🎯 Role-Based Dashboards





Students: Digital Face Card, AI Productivity Nudges, Personal Schedule



Faculty: Classroom Face Scanner, Attendance Analytics, Student Alerts



Administration: Institution-wide Analytics, System Monitoring, Data Insights

🔬 AI-Powered Technology





Face Recognition Attendance: Instant face-scan attendance marking



Productivity Nudges: AI-generated suggestions during free periods



Smart Analytics: Data-driven insights and predictive analytics



Real-time Monitoring: Live attendance tracking and alerts

📊 Advanced Analytics





Interactive charts and data visualization using Recharts



Department performance tracking



Attendance trends and insights



Productivity distribution analysis



Automated reporting system

🎨 Modern UI/UX





Teachmint-inspired clean design



Responsive and mobile-friendly



Calm color palette with educational focus



Rounded cards and modern typography



Smooth animations and transitions

👥 User Roles & Access

🎓 Student Dashboard





Digital Face Card: One-tap attendance marking



AI Productivity Nudges: Smart suggestions for study sessions



Schedule Management: Today's classes and upcoming events



Performance Tracking: GPA, assignments, and goal progress

👨‍🏫 Faculty Dashboard





Classroom Scanner: Bulk attendance via face recognition



Real-time Reports: Live attendance data and analytics



Student Alerts: Notifications for attendance issues



Class Management: Schedule overview and roster access

👨‍💼 Admin Dashboard





Institution Analytics: Campus-wide insights and metrics



Department Performance: Comparative analysis across departments



System Monitoring: Uptime, alerts, and maintenance



Data Visualization: Interactive charts and trend analysis

🔐 Authentication & Security





Firebase Authentication: Secure user management



Role-based Access Control: Separate dashboards for each user type



Protected Routes: Automatic redirection based on user roles



Data Privacy: GDPR-compliant user data handling

## 🛠️ Tech Stack

This project is built with a modern stack, separating the backend logic from a dynamic frontend.

### 🐍 Backend
* **Python:** The core language for all server-side logic.
* **Flask:** A lightweight web framework used to create the web server, handle routes (like `/login`, `/teacher`), and manage API endpoints (like `/submit-teacher`).
* **face_recognition:** The key Python library used for all facial detection and recognition.
* **Numpy:** A dependency for `face_recognition` used for high-performance numerical operations.

### 🌐 Frontend
* **HTML5:** Used for the structure of all web pages (`index.html`, `login.html`, etc.).
* **Tailwind CSS:** A utility-first CSS framework used for styling all the pages and components.
* **JavaScript (ES6+):** Used for all client-side interactivity, including:
    * Handling form submissions (`fetch` API).
    * Requesting and streaming camera access (`navigator.mediaDevices.getUserMedia`).
    * Displaying the demo analytics.
* **Chart.js:** A JavaScript library used to render the "sexy" bar and doughnut charts on the demo dashboard.

### 📦 Development & Deployment
* **Git & GitHub:** Used for version control.
* **virtualenv (venv):** Used to create an isolated Python environment for managing project dependencies.
