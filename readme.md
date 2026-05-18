# User Management Application (Backend)

A robust, scalable RESTful API built with Node.js, Express, and MongoDB (Mongoose) that manages user registration, login, and role-based access for **Users**, **Authors**, and **Admins** using a reusable service architecture.

---

## 🚀 Features & Architecture

* **Role-Based Access:** Clean segregation between regular Users, Authors, and Administrators.
* **Reusable Authentication Service:** Shared core business logic handles registration and authentication across all roles to keep the codebase DRY (Don't Repeat Yourself).
* **Secure Environment:** Centralized configuration management using environment variables.
* **Robust Middleware:** Built-in body parsers and centralized global error handling.

---

## 🛠️ Installation & Setup Guide

Follow these step-by-step instructions to initialize and set up the project locally.

### 1. Initialize Git Repository
Initialize a new local Git repository to begin tracking your changes:
```bash
git init
