# 🏥 The Polyclinic – Healthcare Management System (Preview)

A **multi-tenant healthcare management platform** built with **Next.js 15**, featuring appointment scheduling, user management, drug inventory tracking, and organization management.  

This repository serves as a **public preview** of the project.  
The actual source code is **private** for security and privacy reasons.  
Use the demo link and credentials below to explore the system.

---

## 🚀 Live Preview

🔗 **[View Live Demo](https://demo.divinely.dev)**  

👤 **Demo Credentials**

| Role        | Email             | Password      |
|------------|----------------|--------------|
| Superadmin | superadmin@divinely.dev | password123 |
| Admin      | admin@divinely.dev     | password123 |
| Doctor     | doctor@divinely.dev   | password123 |
| Receptionist  | staff@divinely.dev     | password123 |
| Patient    | patient@divinely.dev   | password123 |

> 🛡️ **Note:** This is a demo environment.  
> Some destructive actions (delete, update critical data) may be disabled.

---

## ✨ Key Features

- **Multi-Tenant Architecture:** Subdomain-based routing for multiple organizations  
- **Role-Based Access Control:** 7 roles (superadmin, moderator, ops, admin, receptionist, doctor, patient)  
- **Appointment Scheduling:** Calendar-based booking and management  
- **User & Organization Management:** Complete admin and staff dashboards  
- **Drug Inventory Tracking:** Manage medications, dosages, and stock levels  
- **Service Catalog:** Configure procedures and prices per organization  
- **Email Notifications:** OTP verification, appointment confirmations, and more  
- **Data Export:** Download users, drugs, appointments as Excel files  
- **Secure Authentication:** OTP-based verification + JWT token handling  
- **Responsive Dashboard:** Real-time analytics and reporting  

---

## 🏗️ Architecture

| Layer         | Tech Stack |
|--------------|-----------|
| **Frontend** | Next.js 15 (App Router), React 19, TypeScript |
| **UI** | HeroUI (NextUI), Tailwind CSS |
| **Backend** | Next.js API Routes + Server Actions |
| **Database** | MongoDB + Mongoose |
| **Auth** | NextAuth.js with OTP verification |
| **State** | React Query (TanStack Query), Zustand |
| **Email** | Nodemailer + Custom Templates |
| **Deployment** | Docker + Vercel |
| **Monitoring** | Sentry |
| **Tooling** | ESLint, Prettier, Husky, Commitlint |

---

## 📋 User Roles & Permissions

| Role        | Permissions |
|------------|-------------|
| Superadmin | Full access, organization management |
| Moderator  | User management, oversight |
| Ops        | Operational management |
| Admin      | Clinic management, staff oversight |
| Receptionist | Appointment scheduling, patient management |
| Doctor     | Patient care, appointment management |
| Patient    | Personal appointments, profile management |

---

## 🖼️ Preview Screenshots

| Dashboard | Appointment Booking | Drug Inventory |
|----------|-------------------|---------------|
| ![Dashboard](./screenshots/dashboard.png) | ![Appointment](./screenshots/appointment.png) | ![Inventory](./screenshots/inventory.png) |

---

## 📚 Documentation

This repository includes:

- **Feature Overview** (You are here)
- **Live Preview Access**
- **API Samples & Workflow Explanation**

> For full **API documentation**, **developer setup guides**, and **self-hosted deployment instructions**,  
> please [contact me](mailto:ankit@divinely.dev) for access to the private repository.

---

## 🤝 Contributing / Access

- Request access to the private repository if you are evaluating this project for production.
- Report issues or suggest features in [GitHub Issues](../../issues).
- For enterprise collaboration or customization, email **ankit@divinely.dev**.

---

## 📄 License

This project is licensed under the **MIT License** – see the LICENSE file for details.

---

Built with ❤️ for healthcare professionals.
