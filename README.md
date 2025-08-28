# Student Management System — Next.js/React

A full-stack **web application** for managing students, instructors, courses, sections, registration, and grade submission. Built with **Next.js/React**.  

This project was completed in **two phases**:  
- Phase 1: JSON-based storage & basic features.  
- Phase 2: Database with Prisma + advanced statistics & authentication.  

---

## 🗂 Repository Structure
- web_project_phase1/ # Phase 1 implementation (JSON-based)
- web_project_phase2/ # Phase 2 implementation (DB + Prisma)
- login.js # Login logic (sample file)
- project_description_phase1.pdf # Phase 1 requirements
- project_description_phase2.pdf # Phase 2 requirements
- web_Project Phase 1_Report.docx # Detailed report (Phase 1)
- web_Project Phase 2_Report.docx # Detailed report (Phase 2)


---

## ✨ Features

### Phase 1 (Foundations)
- User login (from `users.json`).  
- Course search (by name or category).  
- Student registration with prerequisite checks.  
- Learning path view.  
- Admin: validate/cancel courses, create new courses.  
- Instructor: submit student grades.  

### Phase 2 (Advanced)
- Designed **relational data model** with Prisma.  
- Migrated JSON → relational database (SQLite/Postgres/Oracle).  
- Implemented repositories with **DB-side filtering/aggregation**.  
- Added **REST APIs** and **Next.js Server Actions**.  
- Built **analytics/statistics dashboard** (10+ queries: e.g., top courses, failure rates, totals per year).  
- Implemented **authentication** (username/password + GitHub/Google OAuth).  

---

## 🧱 Tech Stack
- **Frontend**: Next.js (React), HTML/CSS/JS  
- **Backend**: Node.js, Next.js Server Actions, REST APIs  
- **Database**: Prisma ORM (SQLite/Postgres/Oracle)  
- **Auth**: NextAuth (credentials + OAuth providers)  

---

## 🚀 Getting Started
### Phase 1
1. Clone the repo.  
2. Navigate to `web_project_phase1/`.  
3. Run `npm install && npm run dev`.  
4. Test login using seeded JSON users.  

### Phase 2
1. Navigate to `web_project_phase2/`.  
2. Configure database in `schema.prisma`.  
3. Run `npx prisma migrate dev && npx prisma db seed`.  
4. Start the dev server: `npm run dev`.  
5. Access statistics dashboard via `/stats`.  

---

## 🧪 Testing
- Screenshots of login, registration, and course flows (Phase 1).  
- DB queries validated with Prisma (Phase 2).  
- Tested authentication with both credentials and GitHub OAuth.  

---

## 📄 Documentation
- `project_description_phase1.pdf` — Requirements (Phase 1)  
- `project_description_phase2.pdf` — Requirements (Phase 2)  
- `web_Project Phase 1_Report.docx` — Implementation & Testing (Phase 1)  
- `web_Project Phase 2_Report.docx` — Implementation & Testing (Phase 2)  

---

## 🗺 Future Enhancements
- Role-based dashboards (Student/Instructor/Admin).  
- Advanced analytics visualizations (charts, graphs).  
- Deployment on Vercel with DB hosting.  
