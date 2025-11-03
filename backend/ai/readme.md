# AI Recommendation System

## 🎯 Purpose
Matches students to the best internship opportunities based on skills, completed courses, and profile data.

## 🧠 Functionality
- Collects student skill data from SkillHub.
- Collects internship data from Industry Module.
- Uses similarity algorithms (cosine similarity / keyword mapping) to rank matches.

## 🧩 API Endpoints
| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | /api/ai/recommend/:student_id | Return ranked list of matching internships |

## 🔗 Integration
- Reads data from Student, SkillHub, and Industry modules.
- Returns recommendation list to Student Portal.
