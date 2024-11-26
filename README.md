# Empowering-Rural-Education
Programming 
## Project Description

Empowering Rural Education through Technology Integration is a platform designed to bridge the gap in education access for rural communities. It leverages technology to deliver educational content, manage student data, and facilitate teacher-student interactions effectively.
## Features
- User roles: Student, Teacher, Administrator.
- Core functionalities: 
  - Students can access lessons and submit assignments.
  - Teachers can create lessons and grade assignments.
  - Administrators can manage users and generate reports.
- Intuitive user interface for ease of navigation.
## Tech Stack
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite
- **Hosting**: Publicly accessible via [insert hosting platform, e.g., Heroku, Vercel]
## Installation and Setup

Follow these steps to set up the project on your local machine:

### Prerequisites
- Python 3.10 or higher installed on your system
- A GitHub account to clone the repository

### Steps
1. Clone the Repository:
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
flask db init
flask db migrate
flask db upgrade
flask run

---

#### **6. Usage Instructions**
```markdown
## Usage Instructions

1. **Students**:
   - Log in and view lessons.
   - Submit assignments.

2. **Teachers**:
   - Log in and create lessons.
   - Grade submitted assignments.

3. **Administrators**:
   - Manage users (add, delete, update).
   - Generate reports for system activity.
