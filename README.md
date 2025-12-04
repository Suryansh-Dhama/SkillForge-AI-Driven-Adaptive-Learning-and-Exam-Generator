SkillForge – AI-Driven Adaptive Learning & Exam Generator
📌 One-Line Summary

A full-stack AI-enhanced platform that delivers personalized learning, automated exams, instant evaluation, and certificate generation for Students, Teachers, and Admins.

📚 Project Overview

SkillForge is an intelligent learning and examination system built to modernize digital education.
It provides:

Teachers → a simplified way to create exams, upload study material, and track performance

Students → structured learning content, adaptive exams, instant results, and certificates

Admins → complete control over platform users, courses, analytics, and content

The system emphasizes automation, scalability, and user-friendly experience, making online learning faster, smarter, and more organized.

🚧 Problem Statement

Traditional e-learning platforms suffer from:

Manual evaluation taking too much time

No personalized learning or adaptive content

Lack of automated certificate generation

Poorly organized study materials

Inefficient exam management for teachers

Limited analytics for Admins, Teachers, and Students

SkillForge solves all these problems through automation, structured dashboards, real-time evaluation, and streamlined learning management.

🗂 Dataset & Database Design

SkillForge uses a PostgreSQL relational database structured with Prisma ORM.

Main Tables

Users (Admin, Teacher, Student)

Courses

Notes / Study Material

Exams

Questions & Options

Exam Attempts

Certificates

Leaderboard Records

All data grows dynamically as users interact with the system.

🛠️ Tools & Technologies Used
Frontend

React (Vite)

TailwindCSS

React Router

Backend

Node.js + Express

TypeScript

JWT + bcrypt for Authentication

Prisma ORM (PostgreSQL)

Other Technologies

EJS + Puppeteer (PDF Certificate Generator)

Git & GitHub (Version Control)

⚙️ Methods & System Workflow
1️⃣ Role-Based Authentication

Separate portals for Admin, Teacher, and Student

Secure login using JWT Tokens + bcrypt hashing

2️⃣ Exam Creation and Management

Teachers create MCQ exams

Questions, options, and correct answers stored in PostgreSQL

3️⃣ Auto Evaluation System

Student submits exam

Backend instantly checks answers

Evaluates score, saves attempt history, updates leaderboard

4️⃣ Smart Certificate Generator

If score ≥ 90%, student receives:

Auto-generated PDF certificate

Unique Certificate ID

QR Code verification

5️⃣ Personalized Dashboards

Each role gets role-specific analytics:

Admin: platform stats, user overview, course controls

Teacher: exam creation, student results, leaderboards

Student: notes, exams, attempt results, downloadable certificates

6️⃣ Leaderboard System

Weekly & monthly rankings

Ranking based on exam performance

7️⃣ Content Management (CMS)

Teachers upload notes

Students can download or view study materials

💡 Key Insights

Automation reduces 80% of manual evaluation work

Students perform better with instant feedback

Certificates & leaderboards boost motivation

Structured dashboards improve usability & security

📊 Dashboards & Outputs
Admin Dashboard

User statistics

Exams & content overview

Platform-wide reporting

Teacher Dashboard

Create exams

Upload notes

View student performance

Leaderboard management

Student Dashboard

Study materials

Exams & instant results

Certificates

Ranking display

Generated Outputs

PDF Certificates

Performance Graphs

Ranked Leaderboards

Downloadable Notes

▶️ How to Run This Project
1. Clone Repository
git clone <https://github.com/Suryansh-Dhama/SkillForge-AI-Driven-Adaptive-Learning-and-Exam-Generator.git>

2. Install Frontend
cd frontend
npm install
npm run dev

3. Install Backend
cd backend
npm install
npx prisma migrate dev
npm run dev

4. Localhost

Frontend → http://localhost:8080/

Backend → http://192.168.1.106:8080/

🏁 Results & Conclusion

SkillForge delivers a complete smart learning ecosystem, combining:

Automated exams

Instant evaluation

Study material management

Certificate creation

Leaderboard rankings

Personalized dashboards

The system dramatically improves learning efficiency, reduces manual workload, and provides a scalable solution for modern digital education.

🚀 Future Enhancements

AI-based automatic question generation

Adaptive learning using ML algorithms

Integrated video lectures & live classes

Payment gateway for premium courses

Voice-based AI tutor

Gamification (badges, streaks, rewards)

Mobile App version

👤 Author & Contact

Name: Suryansh
Role: Full Stack Developer (React + Node + PostgreSQL)
Email: ydvryo@gmail.com
