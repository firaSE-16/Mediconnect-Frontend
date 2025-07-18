# 🏥 MediConnect — Multi-Hospital Management System

🔗 **Live Demo:** [Visit MediConnect](https://medi-front.vercel.app)

![App Screenshot]([<PLACEHOLDER_FOR_DASHBOARD_IMAGE>](https://github.com/user-attachments/assets/7c4d0bbe-8af0-4aae-b6f7-1cd3cbfe677c))
> *(Replace the placeholder with your dashboard screenshot)*

---

## 📖 Overview

**MediConnect** is an advanced and scalable multi-hospital management system designed for smooth coordination among hospitals, doctors, patients, lab technicians, and administrative staff. It supports full patient treatment flow — from registration and triage to prescriptions and lab results — along with centralized control by system and hospital administrators.

---

## 🧰 Tech Stack

- ⚛️ **Frontend:** React + Vite + ShadCN UI  
- 🌐 **Backend:** Node.js + Express  
- 🧠 **Database:** MongoDB  
- 💄 **UI/UX:** ShadCN UI, Tailwind CSS  
- 🗂️ **PDF Export:** Custom module for printing and saving medical records  
- 🔐 **Authentication:** Role-based access with secure sessions  

---

## 🔐 Demo Login Credentials

You can explore the platform using these **pre-configured demo accounts**:

| Role               | Email                 | Password    |
|--------------------|------------------------|-------------|
| 🛡️ System Admin     | `admin@gmail.com`       | `12345678`  |
| 🏥 Hospital Admin   | `kebed@gmail.com`       | `12345678`  |
| 👩‍⚕️ Doctor          | `selam@gmail.com`       | `12345678`  |
| 🔬 Lab Technician   | `dagim@gmail.com`       | `12345678`  |
| 🧾 Receptionist     | `mahider@gmail.com`     | `12345678`  |
| 🚑 Triage Nurse     | `meron@gmail.com`       | `12345678`  |

> ⚠️ Use appropriate roles for each section to see full functionality.

---

## 🏗️ Key Features

### 👥 Roles & Permissions
- **System Admin**  
  - Register hospitals with valid licenses  
  - Oversee entire system activity

- **Hospital Admin**  
  - Add/manage hospital staff  
  - View full audit logs (who treated who)

- **Receptionist**  
  - Register new patients  
  - Initiate patient medical records

- **Triage Nurse**  
  - Record patient vitals and condition before doctor visit

- **Doctor**  
  - View patient history  
  - Add prescriptions and request lab tests

- **Lab Technician**  
  - Record lab results and upload reports

- **Patient**  
  - Manage profile and view/download PDF records

---

## 🧾 Functional Highlights

- ✅ **Full CRUD** for hospitals, users, patients, and records  
- 🔍 **Audit Logging:** Track every patient-treatment interaction  
- 📄 **PDF Generation:** Export and print prescriptions and lab results  
- 🖥️ **Dynamic Sidebar Navigation** per role  
- 🧩 **Scalable Design** for adding more hospitals or departments  
- 🎯 **Dashboards:** Real-time overview for system and hospital admins  
- 🧠 **Context-based Access:** Role-driven component rendering  

---

## 🖼️ Screenshots

### 🔷 Admin Dashboard
![Dashboard Screenshot](<PLACEHOLDER_FOR_DASHBOARD_IMAGE>)

### 🔶 Doctor Panel
![Doctor Panel Screenshot](<PLACEHOLDER_FOR_DOCTOR_PANEL_IMAGE>)

### 🔷 PDF Record View
![PDF Screenshot](<PLACEHOLDER_FOR_PDF_IMAGE>)

---

## 🚀 Getting Started (Development)

```bash
# Clone the repository
https://github.com/firaSE-16/Mediconnect-Frontend.git

# Navigate into project
cd mediconnect

# Install frontend dependencies
npm install

# Start frontend
npm run dev

#   clone backend repo

.env file

``` CONNSTR=.....
JW_SECRET=......
PORT=....```


cd backend
npm install
npm start
