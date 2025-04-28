# 🏡 Airbnb Clone Project

---

## 📖 Overview
The **Airbnb Clone Project** is a full-stack web application designed to simulate a real-world booking platform like Airbnb.  
It focuses on backend development, database design, API security, and CI/CD practices for building scalable, secure systems.

**🎯 Goals:**
- Build a robust and scalable booking platform.
- Understand complex system architecture.
- Master team collaboration and modern software workflows.

**🛠 Tech Stack:** Django, MySQL, GraphQL, Docker, GitHub Actions

---

## 👥 Team Roles

| Role                  | Responsibility                                                              |
|------------------------|----------------------------------------------------------------------------|
| **Backend Developer**  | Build APIs, manage business logic, and ensure security                     |
| **Database Admin**     | Design schemas, manage data, optimize performance                          |
| **DevOps Engineer**    | Implement CI/CD pipelines and manage deployments                           |
| **Security Specialist**| Protect APIs through authentication, authorization, and data validation   |
| **Project Manager**    | Coordinate tasks, documentation, and ensure timely delivery                |

---

## ⚙️ Technology Stack

- **Django:** Web framework for backend development and RESTful APIs.
- **MySQL:** Structured, scalable relational database system.
- **GraphQL:** Flexible query language for API-client communication.
- **Docker:** Containerization for consistent development and deployment environments.
- **GitHub Actions:** CI/CD automation for testing and deployment.

---

## 🗂️ Database Design

**Entities:**
- **User:** `id`, `name`, `email`, `password_hash`, `role`
- **Property:** `id`, `owner_id`, `title`, `description`, `location`
- **Booking:** `id`, `user_id`, `property_id`, `start_date`, `end_date`
- **Review:** `id`, `user_id`, `property_id`, `rating`, `comment`
- **Payment:** `id`, `booking_id`, `amount`, `status`, `payment_date`

**Entity Relationships:**
- A user can own multiple properties.
- A user can make multiple bookings.
- Each booking is linked to one property.
- Properties can have multiple reviews.
- Each booking has one payment associated.

---

## ✨ Feature Breakdown

- **User Management:** Secure registration, login, and profile management.
- **Property Management:** Add, edit, and remove property listings.
- **Booking System:** Book available properties with date validation.
- **Review System:** Submit and view property reviews after stays.
- **Payment Processing:** Secure handling of booking payments and transactions.

---

## 🔒 API Security Overview

- **Authentication:** JWT-based secure user login.
- **Authorization:** Role-based access control (guests vs owners).
- **Rate Limiting:** Protection against abuse and brute-force attacks.
- **Data Validation:** Prevent malicious input and enforce data integrity.
- **Encryption:** Secure sensitive data like passwords and payments.

**🔑 Why Security Matters:**
- Safeguard personal and financial information.
- Protect the platform from unauthorized access and data breaches.
- Build trust and ensure compliance with security standards.

---

## 🚀 CI/CD Pipeline Overview

- **What is CI/CD?**  
Continuous Integration (CI) and Continuous Deployment (CD) automate code testing, building, and deployment.
  
- **Why it matters:**  
Boosts speed, minimizes human error, ensures stable releases.

- **Tools:**
  - **GitHub Actions:** Automate builds, tests, and deployments.
  - **Docker:** Ensure consistent app environments across systems.

---

## 📁 Repository Link

🔗 [airbnb-clone-project](https://github.com/BaslealAkliluNeymar/airbnb-clone-project)

---
