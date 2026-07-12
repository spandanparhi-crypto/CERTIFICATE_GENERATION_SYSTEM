# 🏆 Certificate Generation System

A modern **Certificate Generation System** that automates certificate creation, management, verification, and distribution for educational institutions, organizations, events, workshops, seminars, and competitions.

The system enables administrators to generate certificates individually or in bulk, while users can securely verify and download their certificates online.

---

# 🌐 Live Demo

**Live Project:** https://odd-white-vbfftlhq.edgeone.dev/

---

# 📖 Overview

The Certificate Generation System is a web-based application that eliminates manual certificate creation by automatically generating professional certificates using participant data and customizable templates.

The application supports QR code verification, PDF generation, bulk certificate creation, and secure certificate validation, making certificate management fast, reliable, and paperless.

---

# ✨ Features

## 👨‍💼 Admin Features

- Secure Admin Login
- Dashboard Overview
- Manage Users
- Manage Events/Courses
- Add Participants
- Upload Participants via CSV/Excel
- Design Certificate Templates
- Generate Individual Certificates
- Bulk Certificate Generation
- Download Certificates as PDF
- Email Certificates to Participants
- Manage Certificate Records
- Certificate Verification Management

---

## 👨‍🎓 User Features

- User Registration
- Secure Login
- View Issued Certificates
- Download Certificates
- Verify Certificates
- View Certificate History
- Profile Management

---

## ⚡ Certificate Features

- Automatic Certificate Generation
- Dynamic Certificate Templates
- Unique Certificate ID
- QR Code Verification
- Digital Signature Support
- PDF Export
- High-Resolution Certificates
- Bulk Certificate Creation
- Email Integration
- Printable Certificates

---

# 🛠️ Tech Stack

## Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap
- Tailwind CSS
- React.js

## Backend

- Node.js
- Express.js

## Database

- MongoDB

## Authentication

- JWT Authentication
- bcrypt Password Encryption

## PDF Generation

- PDFKit
- jsPDF
- html2canvas

## QR Code

- qrcode

## Deployment

- EdgeOne

---

# 📂 Project Structure

```text
Certificate-Generation-System/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── templates/
│   ├── uploads/
│   ├── certificates/
│   ├── server.js
│   └── package.json
│
├── README.md
└── package.json
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/your-username/certificate-generation-system.git
```

## Navigate to Project

```bash
cd certificate-generation-system
```

## Install Dependencies

```bash
npm install
```

## Start Backend

```bash
npm start
```

## Start Frontend

```bash
npm run dev
```

---

# ⚙️ Environment Variables

Create a **.env** file inside the backend directory.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

EMAIL_USER=your_email@gmail.com

EMAIL_PASSWORD=your_email_password
```

---

# 📊 System Workflow

```text
Admin Login
      │
      ▼
Create Event
      │
      ▼
Add Participants
      │
      ▼
Upload CSV (Optional)
      │
      ▼
Choose Certificate Template
      │
      ▼
Generate Certificate
      │
      ▼
Generate PDF
      │
      ▼
Store Certificate
      │
      ▼
Send Email / Download
      │
      ▼
Certificate Verification
```

---

# 📸 Screenshots

- Home Page
- Login Page
- Registration Page
- Admin Dashboard
- Event Management
- Participant Management
- Certificate Template
- Certificate Preview
- PDF Download
- Certificate Verification

---

# 📋 Core Modules

- Authentication Module
- User Management
- Event Management
- Participant Management
- Certificate Template Management
- Certificate Generation Engine
- PDF Export
- Email Notification
- QR Code Verification
- Certificate Validation

---

# 🔒 Security Features

- JWT Authentication
- Password Hashing
- Role-Based Access Control
- Protected API Routes
- Input Validation
- Secure Session Management
- QR-Based Certificate Verification

---

# 📄 Certificate Information

Every generated certificate includes:

- Certificate ID
- Participant Name
- Course/Event Name
- Organization Name
- Issue Date
- QR Code
- Digital Signature
- Verification Link

---

# 📈 Future Enhancements

- AI-Based Certificate Designer
- Multiple Certificate Templates
- Blockchain Certificate Verification
- Cloud Storage Integration
- Multi-language Support
- SMS Notifications
- Organization Branding
- Analytics Dashboard
- Mobile Application

---

# 💡 Advantages

- Automatic Certificate Generation
- Saves Time
- Paperless Process
- Bulk Certificate Creation
- QR Code Verification
- Secure Authentication
- Easy PDF Download
- Email Distribution
- Responsive Design
- User-Friendly Interface

---

# 🌐 Live Demo

**Project Link:** https://odd-white-vbfftlhq.edgeone.dev/

---

# 👨‍💻 Author

**Spandan Parhi**
---

# 📄 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you found this project helpful, please consider giving it a **⭐ Star** on GitHub.

---

## 🙏 Acknowledgements

Thanks to all the open-source libraries and tools that made this project possible.
