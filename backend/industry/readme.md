# Industry Module

## 🎯 Purpose
Provides an interface for industries to **post internships**, view applicants, and manage selections.

## 🧩 API Endpoints
| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | /api/industry/register | Register industry account |
| POST | /api/industry/login | Login and receive token |
| POST | /api/industry/post | Post a new internship |
| GET | /api/industry/list | View all active internships |
| GET | /api/industry/applicants/:internship_id | View student applications |

## 🗂️ Database Tables
- **industry**
- **internships**

## 🔗 Integration
- Works with **Student Module** (internship applications).
- Feeds internship data to **AI Module** for recommendations.
