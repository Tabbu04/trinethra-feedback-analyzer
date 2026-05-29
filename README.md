# Trinethra — Supervisor Feedback Analyzer

An AI-powered web application that analyzes supervisor feedback transcripts 
about Fellows (interns/consultants) and generates structured insights.

Built as part of the DeepThought Software Developer assignment.

## What It Does

- Extracts quoted evidence from transcripts (positive, negative, neutral)
- Scores the Fellow on a rubric from 1–10 with justification
- Maps performance to relevant KPIs
- Identifies gaps — topics the supervisor didn't cover
- Suggests follow-up questions for deeper evaluation

## Tech Stack

- **Frontend:** HTML, CSS, Vanilla JavaScript
- **Backend:** Python, FastAPI
- **AI:** Ollama running llama3.2 locally

## How To Run

### 1. Install Ollama
Download from ollama.com and run:

### 2. Install Python dependencies

### 3. Start the backend

### 4. Open the frontend
Open `frontend/index.html` in your browser.

## What I'd Improve Next

- Fix occasional missing positive evidence in AI output
- Add export to PDF feature
- Add comparison view for multiple Fellows
- Deploy backend to a cloud server so it works without local Ollama
