
 Relationship Health Monitor 

Basic Details

Team Name:Technova

Team Members

Member 1: Agreesha – Mar Athanasius College of Engineering
Member 2: Angela Aliyamma Regi –Mar Athanasius College of Engineering

 Hosted Project Link

[https://your-project-link.com](https://your-project-link.com)

---

## Project Description

Relationship Health Monitor is an AI-powered web application that analyzes text messages and voice recordings to detect red flags and green flags in relationships. It evaluates emotional patterns, assigns a health score, and provides supportive insights to help users recognize toxic or healthy communication.

---

## The Problem Statement

Many people experience emotional manipulation, gaslighting, guilt-tripping, or unhealthy communication in relationships but fail to recognize these patterns early. Subtle toxic behaviors often go unnoticed until serious emotional harm occurs.

---

## The Solution

Our solution uses AI to analyze conversations (text or audio) and detect behavioral patterns in real time. The system identifies red flags, green flags, calculates a relationship health score, and provides actionable insights and support resources to empower users with awareness.

---

# Technical Details

## Technologies/Components Used

### For Software

**Languages used:**

* JavaScript
* Python
* HTML
* CSS

**Frameworks used:**

* FastAPI

**Libraries used:**

* Pydantic
* Fetch API
* MediaRecorder API

**Tools used:**

* VS Code
* Git & GitHub
* Uvicorn
* Groq API

---

# Features

Feature 1: Text Message Analysis – Detects red and green flags from typed conversations.

Feature 2: Voice Recording Analysis – Records voice notes directly in the browser and analyzes them.

Feature 3: Audio File Upload – Supports MP3, WAV, M4A for analyzing call recordings or WhatsApp voice notes.

Feature 4: Relationship Health Score – Generates a score (0–100) with grade (TOXIC, MIXED, GOOD, etc.).

Feature 5: Structured Emotional Report – Provides explanation, actionable advice, and support resources.

Feature 6: Privacy-Focused – No user data is stored.

---

# Implementation

## For Software

### Installation

```bash
git clone https://github.com/your-username/relationship-health-monitor.git
cd relationship-health-monitor
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # Mac/Linux
pip install -r requirements.txt
```

---

### Run

```bash
uvicorn app.main:app --reload
```

Open in browser:

```
http://127.0.0.1:8000
```

---

# Project Documentation

Relationship Health Monitor works in three main stages:

1. Input Stage – User enters text or uploads/records audio.
2. Processing Stage – Audio is transcribed using Whisper AI, then analyzed using LLM.
3. Output Stage – The system returns structured JSON containing red flags, green flags, health score, grade, and supportive insights.

The application is designed as an awareness and educational tool to promote emotional safety and healthier communication.

---

If you want, I can now:
✅ Make this more professional (judge-ready version)
✅ Add architecture diagram section
✅ Add screenshots section
✅ Customize with your actual team names and college
✅ Reduce to 1-page compact version

Tell me what you want next 🚀
