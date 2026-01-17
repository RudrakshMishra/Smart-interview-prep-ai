# Smart-interview-prep-ai
AI-powered mock interview platform that simulates real interviews, evaluates answers using LLMs, and provides personalized feedback with progress tracking.
# Smart Interview Prep AI 
An AI-powered mock interview platform that simulates real interviews,
evaluates answers, provides structured feedback, and tracks user progress
using Large Language Models (LLMs).

---

##  Overview
Smart Interview Prep AI helps candidates prepare for technical and behavioral
interviews by acting as a personalized AI interviewer.

The system adapts questions based on:
- Target role
- Experience level
- Skill set
- Past performance

---

##  Features (MVP)

- Role-based interview questions
- Real-time AI evaluation of answers
- Structured feedback (strengths & improvements)
- Scoring system (0–10)
- User progress dashboard
- Clean and intuitive UI

---

##  AI Capabilities

- LLM-based question generation
- Context-aware answer evaluation
- Personalized feedback generation
- Hybrid scoring (LLM + rules + keywords)

---

##  Architecture

Frontend (React)
→ Backend API (FastAPI)
→ Interview Engine
→ LLM (OpenAI / Open-source)
→ Database (PostgreSQL / SQLite)

---

## ⚙️ Tech Stack

### AI / ML
- OpenAI GPT / LLaMA / Mistral
- Prompt Engineering
- LangChain (optional)

### Backend
- Python
- FastAPI
- SQLAlchemy
- Pydantic

### Frontend
- React / Vite
- Tailwind CSS
- Chart.js

### Database
- SQLite (MVP)
- PostgreSQL (Production)

---

 Scoring Methodology

Final Score =  
(LLM Evaluation × 0.6) +  
(Keyword Match × 0.2) +  
(Structure & Clarity × 0.2)

---

 Project Structure

See repository structure above.

---

 Roadmap

- Voice-based interviews
- Resume-aware question generation
- Company-specific interview modes
- Multi-agent panel interviews
- SaaS authentication & payments

---

 Screenshots
(Add UI screenshots here)

---

 Author
Rudraksh Mishra

---

 License
MIT License
