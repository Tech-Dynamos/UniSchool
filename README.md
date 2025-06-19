# UniSchool
# 🏫 UniSchool – Multi-Tenant Education Management System

[![Made with React] 

<p align="center">
  <img src="https://github.com/attariCreation/UniSchool_React_javascript/blob/main/src/assets/images/logo.png" alt="UniSchool Logo" width="300"/>
</p>

**UniSchool** is a modern, scalable, and secure multi-tenant school management platform. Each school gets its own workspace to handle academic, administrative, and communication needs—all from a single interface.

## 📚 Table of Contents

1. [Overview](#-overview)
2. [Public Access & School Creation](#-public-access--school-creation)
3. [Role-Based User Flow](#-role-based-user-flow)
4. [Dashboard Structure](#-dashboard-structure)
5. [School Customization & Theme](#-school-customization--theme)
6. [Join Mechanism & Approval System](#-join-mechanism--approval-system)
7. [Tech Stack](#-tech-stack)
8. [Setup](#-setup)
9. [License](#-license)

## 🧭 Overview

UniSchool is a **multi-tenant education management system** that enables schools to manage academics, staff, students, and parents through a secure role-based dashboard. Each school gets its own independent workspace within the platform.

---

## 🌐 Public Access & School Creation

The public-facing section includes:

- Landing page
- School registration
- Login & join pages

🛡️ **Only principals** can create schools, each getting a unique School ID. Teachers and admins are added by the principal. Students and parents can join using:

- Invite links (auto-add)
- School ID (manual approval)

---

## 👥 Role-Based User Flow

### 🧑‍🏫 Principals
- Create/manage school
- Add staff and configure settings

### 🛠️ Admins
- HODs, finance, library staff with role-based permissions

### 👨‍🏫 Teachers
- Manage courses, assignments, attendance

### 🎓 Students
- Join via invite or request
- Access lessons, homework, grades

### 👨‍👩‍👧 Parents
- Request to join
- Connect to child and monitor progress


<p align="center">
  <img src="https://github.com/attariCreation/UniSchool_React_javascript/blob/main/src/assets/images/managment2.webp" width="600"/>
</p>

## 🎨 School Customization & Theme

Each school can choose its **dashboard color theme**, which is stored in the database and applied dynamically.

- Principals can preview and apply themes
- Public pages retain UniSchool’s branding

## 🔐 Join Mechanism & Approval System

Students and Parents join via:

1. **Secure Invite Link** – Auto-added to the school
2. **Join Request** – Fill form using School ID → Approval required

🧾 Parents can link to their children after joining through a secure request system.

<p align="center">
  Keep Learning 
  <img src="https://github.com/attariCreation/UniSchool_React_javascript/blob/main/src/assets/images/unischool2.webp" width="600"/>
</p>


## 🧰 Tech Stack

- **Frontend:** React.js(vite), TailwindCSS, NEXTJS, HTML, CSS 
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Auth:** JWT, Role-based, FIREBASE
- **Others:** REST API, Multi-tenant architecture

- ## 🛠️ Setup

```bash
git clone https://github.com/Tech-Dynamos.UniShool.git
cd UniSchool
npm install
npm run dev



Thanks for checking out **UniSchool**! 🎓  
We hope it helps bring more structure, clarity, and collaboration to schools everywhere.

If you have ideas, questions, or want to contribute —  
don’t be a stranger. 🤝

📬 [Contact us](mailto:abdulhannan.dev.official@gmail.com)  
⭐ Don’t forget to star the repo if you liked it!

Stay curious,  
**– The TechDynamos **

---
