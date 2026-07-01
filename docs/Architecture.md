# Architecture

Current Architecture

User

↓

Frontend (HTML/CSS/JavaScript)

↓

Future Backend

↓

Database

↓

AI Services

---

Future Architecture

                User
                  │
                  ▼
           Frontend (React)
                  │
                  ▼
          Backend API (Node.js)
                  │
      ┌───────────┼───────────┐
      ▼           ▼           ▼
 Database     AI Services   Authentication
(PostgreSQL) (OpenAI)      (Clerk/Firebase)

                  │
                  ▼
          External APIs