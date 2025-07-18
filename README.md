# 🏥 MediConnect — Multi-Hospital Management System

🔗 **Live Demo:** [Visit MediConnect](https://medi-front.vercel.app)

![App Screenshot](<PLACEHOLDER_FOR_DASHBOARD_IMAGE>)
> *(Replace the placeholder with your dashboard screenshot)*

---

## 📖 Overview

**MediConnect** is an advanced and scalable multi-hospital management system built for seamless coordination between healthcare professionals and patients. It empowers hospitals to manage staff, track treatments, and generate detailed records — all under one robust platform.

This system handles end-to-end operations, including patient registration, triage assessment, doctor consultation, lab requests, and centralized hospital administration.

---

## 🧰 Tech Stack

- ⚛️ **Frontend:** React + Vite + ShadCN UI  
- 🧠 **State Management:** React Context API  
- 🌐 **Backend:** Node.js + Express  
- 🗃️ **Database:** MongoDB  
- 📦 **UI/UX:** ShadCN UI, Tailwind CSS  
- 🖨️ **PDF Exporting:** Custom PDF print module  
- 🔒 **Auth & Audit:** Role-based access control and action logging  

---

## 🏗️ Key Features

### 👥 Roles and Access
- **Central System Admin**  
  - Register hospitals with valid licenses  
  - Oversee all system activity  

- **Hospital Admin**  
  - Add hospital staff (Doctors, Receptionists, Lab Technicians, Triage Nurses)  
  - View audit logs (who treated whom, when, and where)  
  - Monitor hospital-wide activities  

- **Receptionist**  
  - Register new patients  
  - Initiate patient medical records  

- **Triage Nurse**  
  - Perform initial patient assessments  
  - Record vitals and condition  

- **Doctor**  
  - Diagnose and treat patients  
  - Prescribe medications and request lab tests  

- **Lab Technician**  
  - View lab test requests  
  - Record and upload test results  

- **Patient**  
  - Register and manage appointments  
  - Download medical records in PDF format  

---

## 📄 Core Functionalities

- ✅ Full **CRUD** operations for all major modules  
- 🔍 **Audit Logs**: Track who treated which patient and when  
- 🧾 **PDF Generation**: Export medical records, prescriptions, and lab results  
- 🧠 **Role-Based Dashboards**: Clean and modern dashboards for each user role  
- 🗂️ **Sidebar Setup**: Intuitive and dynamic sidebar navigation  
- ⚙️ **Scalable Structure**: Built to support multi-hospital environments  
- 💬 **Clean UI/UX**: Built with ShadCN components for consistency and speed  
- 🔒 **Secure API**: Access control and validation at every endpoint  

---

## 🖼️ Screenshots

### 🔷 Dashboard Example
![Dashboard Screenshot](<PLACEHOLDER_FOR_DASHBOARD_IMAGE>)

### 🔶 Doctor Panel
![Doctor Panel Screenshot](<PLACEHOLDER_FOR_DOCTOR_PANEL_IMAGE>)

### 🔷 PDF Record View
![PDF Screenshot](<PLACEHOLDER_FOR_PDF_IMAGE>)

---

## 🚀 Getting Started (Development)

```bash
# Clone the repository
git clone https://github.com/firaSE-16/mediconnect-

# Navigate into the folder
cd medi-connect

# Install dependencies (for both frontend & backend)
npm install

# Start frontend
npm run dev

# Start backend (make sure MongoDB is running)
cd backend
npm run start
