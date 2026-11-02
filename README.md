# InkFlow — Full-Stack Blogging Platform

InkFlow is a modern blogging platform built with FastAPI and Python that allows users to create, manage, and share blog posts through a clean and responsive interface. It combines a powerful backend with secure authentication and database management.

##  Features

- **User Authentication:** Secure user registration and login.
- **Blog Management:** Create, read, update, and delete blog posts.
- **JWT Authentication:** Secure API endpoints with token-based authentication.
- **Database Integration:** Store and manage application data using PostgreSQL and SQLAlchemy.
- **Input Validation:** Validate incoming requests using Pydantic.
- **Responsive UI:** User-friendly interface built with HTML, CSS, Bootstrap, and JavaScript.
- **API Documentation:** Interactive API documentation using Swagger UI.
- **Modular Architecture:** Organized backend code for maintainability and scalability.

##  Tech Stack

| Category | Technologies |
|---|---|
| Language | Python |
| Backend | FastAPI |
| Database | PostgreSQL |
| ORM | SQLAlchemy |
| Validation | Pydantic |
| Authentication | JWT, Password Hashing |
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Templates | Jinja2 |
| API Testing | Swagger UI, Postman |
| Version Control | Git, GitHub |

##  Project Structure

```text
InkFlow/
├── app/
│   ├── routers/
│   ├── models/
│   ├── schemas/
│   ├── database.py
│   └── main.py
├── templates/
├── static/
├── tests/
├── requirements.txt
├── .env.example
└── README.md
```

*Note: The directory structure may vary depending on the implementation.*

##  Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Sridioite/InkFlow.git
cd InkFlow
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate the environment:

**Windows**
```bash
.venv\Scripts\activate
```

**Linux / macOS**
```bash
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file and configure the required variables:

```env
DATABASE_URL=postgresql://username:password@localhost:5432/inkflow
SECRET_KEY=your_secret_key
ALGORITHM=HS256
```

Replace the database credentials and secret key with your own values.

### 5. Run the Application

```bash
uvicorn app.main:app --reload
```

The application will be available at:

http://127.0.0.1:8000

##  API Documentation

FastAPI provides interactive API documentation.

- **Swagger UI:** http://127.0.0.1:8000/docs
- **ReDoc:** http://127.0.0.1:8000/redoc

## 🔐
InkFlow uses JWT-based authentication to secure protected endpoints.

Users can register, log in, and access authorized resources using authentication tokens.

##  Project Objective

The primary objective of InkFlow is to demonstrate practical backend development skills, including REST API design, database integration, authentication, data validation, and full-stack application development using FastAPI.

##  Author

**Abhishek**

- GitHub: [@Sridioite](https://github.com/Sridioite)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/abhishekkji/)

---

⭐ If you find this project interesting, consider giving it a star!
