# AI Interview Coach

AI Interview Coach is a full-stack application designed to help users prepare for technical interviews through personalized interview practice, AI-powered question generation, and performance analysis.

The project is being developed with a modern full-stack architecture, with a FastAPI backend, MongoDB database, and a frontend application.

## 🚀 Current Progress

### Backend Foundation — Completed

- User registration
- User login
- JWT-based authentication
- Authenticated current-user endpoint
- Interview creation
- Retrieve all user interviews
- Retrieve a single interview
- Update interviews
- Delete interviews
- User-specific interview data protection
- Automated backend API testing with PowerShell
- MongoDB database integration

### AI Features — In Development

Planned AI capabilities include:

- AI-generated interview questions
- Personalized technical interview sessions
- Answer evaluation
- Interview feedback
- Performance analysis
- Improvement recommendations

---

## 🏗️ Tech Stack

### Backend

- **Python**
- **FastAPI**
- **MongoDB**
- **PyMongo**
- **JWT Authentication**
- **Passlib / bcrypt**

### Frontend

- **React**
- **JavaScript**
- **HTML**
- **CSS**

### Development Tools

- **Git & GitHub**
- **VS Code**
- **PowerShell**

---

## 📁 Project Structure

```text
AI-Interview-Coach/
│
├── Frontend/
│
├── backend/
│   │
│   ├── app/
│   │   ├── api/
│   │   │   ├── auth.py
│   │   │   └── interview.py
│   │   │
│   │   ├── core/
│   │   │   └── security.py
│   │   │
│   │   ├── database/
│   │   │   └── database.py
│   │   │
│   │   ├── models/
│   │   │   └── interview.py
│   │   │
│   │   ├── schemas/
│   │   │   ├── user.py
│   │   │   └── interview.py
│   │   │
│   │   └── main.py
│   │
│   ├── test_api.ps1
│   └── requirements.txt
│
├── .gitignore
└── README.md
