# Configuration Module

## 🎯 Purpose
Houses all configuration files for database setup, environment variables, and shared constants.

## 📂 Files
- **db_config.py** → Database connection (SQLAlchemy)
- **.env** → Environment variables (kept in root directory)

## 🧰 Usage
All backend modules import the same configuration:
```python
from backend.config.db_config import db
