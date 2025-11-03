# Skill Readiness Hub

## 🎯 Purpose
Provides pre-internship courses, quizzes, and gamified progress tracking to prepare students for industry exposure.

## 🧩 API Endpoints
| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | /api/skillhub/courses | List available courses |
| POST | /api/skillhub/complete/:course_id | Mark course completion |
| GET | /api/skillhub/progress/:student_id | Fetch progress & badges |

## 🔗 Integration
- Sends skill data to **AI Module** for improved recommendations.
- Displays progress in **Student Dashboard**.
