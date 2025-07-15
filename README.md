# 🎓 Campus Recruitment System (CRS)

The **Campus Recruitment System (CRS)** is a web-based application designed to streamline the recruitment process between students, placement officers, and recruiting companies in an academic institution. This platform ensures efficient communication, transparency, and automation of recruitment workflows — making the entire process more effective and less time-consuming.

---

## 🛠️ Features

### 👨‍🎓 Student Portal
- Apply for jobs and upload academic documents.
- Track job application status.
- Search for available job openings.
- Secure login with credential verification.

### 🏢 Company Portal
- Register and post job openings.
- View applications and shortlist candidates based on eligibility.
- Schedule interviews and notify selected candidates.

### 👨‍💼 Admin & Coordinator Dashboard
- Manage student and company profiles.
- Oversee recruitment process across all users.
- Generate and distribute final selection lists.
- Monitor system activity and placement stats.

### 🔐 Security & Verification
- Integration with National Academic Depository (NAD) for academic record verification.
- Secure authentication for all user types.

### 📊 Analytics & Reporting
- Placement statistics and engagement analytics for coordinators.
- Transparent, stage-wise tracking of the recruitment process.

---

## 📌 System Architecture

The system follows a modular architecture, comprising the following core entities (as per the UML class diagram):

- **Student**
- **Admin**
- **Company**
- **Jobs**
- **Registration**
- **UserLogin**

Each module includes relevant fields and methods to handle functionality such as login, registration, job management, and verification.

📎 *Refer to the UML Class Diagram in the `/docs` folder for full object relationships and structure.*

---

## 🧾 Flow of the System

1. **Student Registration & Login** → Upload academic details → Get verified via NAD.
2. **Company Registration** → Set eligibility criteria → Post job openings.
3. **System Shortlisting** → Students apply → Interview schedule generation.
4. **Recruitment Rounds** (Aptitude, Technical, HR) → Stage-wise list updates.
5. **Final Selections** → Lists shared with Admin & Companies.
6. **Admin Oversight** → Handles entire flow and communication.

---
