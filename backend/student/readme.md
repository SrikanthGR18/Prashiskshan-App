
---

## 👨‍🎓 **`/backend/student/` – `README.md`**
```markdown
# Student Module

## 🎯 Purpose
Handles all **student-related functionalities** including registration, profile management, internship browsing, and application tracking.

## 🧩 API Endpoints
| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | /api/student/register | Register a new student |
| POST | /api/student/login | Student login (JWT) |
| GET | /api/student/profile/:id | Get student details |
| GET | /api/student/internships | View available internships |
| POST | /api/student/apply/:internship_id | Apply for internship |

## 🗂️ Database Tables
- **students** – stores student info  
- **applications** – tracks internship applications

## 🔗 Integration
- Connects with **Industry Module** for internship listings.
- Communicates with **Logbook Module** to track internship progress.
