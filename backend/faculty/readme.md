# Faculty & Admin Module

## 🎯 Purpose
Allows faculty members to **verify internship progress**, **approve logbooks**, and **assign credits** as per NEP 2020.

## 🧩 API Endpoints
| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | /api/faculty/login | Faculty login |
| GET | /api/faculty/students | List students under supervision |
| PUT | /api/faculty/verify-log/:entry_id | Approve or reject logbook entry |
| GET | /api/faculty/reports | View reports & credit summaries |

## 🔗 Integration
- Communicates with **Logbook Module** for student progress.
- Updates **InternshipSummary** table with approval remarks.
