# Uptoskills AI Learning Platform

A full-stack role-based e-learning platform built with React.

## Features
- **Role-based Authentication**: Separate views and permissions for Students and Admins.
- **Student Dashboard**: Browse courses, enroll with a preferred "Instructor Style", track lesson progress, and generate certificates.
- **Admin Dashboard**: View platform metrics, manage courses, and monitor student progress.
- **Dark/Light Theme**: Persistent theme switcher built with Tailwind CSS.

## Prerequisites
- Node.js (v18+)
- PostgreSQL running locally (default port 5432)

## Setup Instructions

### 1. Database Setup
1. Ensure PostgreSQL is running.
2. In your terminal, navigate to the `backend` folder:
   ```bash
   cd backend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Configure your `.env` file inside the `backend` directory (default credentials are provided but you can change them).
5. Seed the database with the initial schema, admin user, and sample courses:
   ```bash
   npm run seed
   ```

### 2. Running the Backend
In the `backend` folder, start the Express server:
```bash
npm run dev
```
*The server will run on http://localhost:5000*

### 3. Running the Frontend
In a separate terminal, navigate to the root directory (frontend) and install dependencies:
```bash
npm install
```
Start the Vite development server:
```bash
npm run dev
```
*The application will run on http://localhost:5174 or similar.*

## Default Test Accounts
After running the seed script, you can log in with:

**Admin:**
- Email: `admin@example.com`
- Password: `admin123`

**Student:**
- Email: `student@example.com`
- Password: `student123`
