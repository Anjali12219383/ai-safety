




## ⚙️ Getting Started

```bash
# Clone the repository
git clone https://github.com/AnjiOnGit/ai-safety.git
cd ai-safety

# (Optional) Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Safe_Unsafe_Examples.ipynb
# AI Safety Incident Dashboard

This is a simple and interactive **AI Safety Incident Dashboard** built with **React**, **TypeScript**, and **CSS**.

It allows users to:
- View a list of AI safety incidents
- Filter incidents by severity
- Sort incidents by date (Newest First / Oldest First)
- Expand incident details
- Report (add) a new incident

All data is handled locally within the frontend application memory. No backend integration is required.

---

## Tech Stack

- **React** (Frontend Framework)
- **TypeScript** (Type Safety)
- **Vite** (Development Tool)
- **CSS** (Styling)

---


---

## Features

Display a list of AI incidents  
Filter incidents by severity ("All", "Low", "Medium", "High")  
Sort incidents by Reported Date (Newest First, Oldest First)  
Expand/Collapse incident description  
Report a new incident through a form  
Basic input validation (no empty fields)  
Responsive and clean UI layout

---

## Mock Data Used

```json
[
  {
    "id": 1,
    "title": "Biased Recommendation Algorithm",
    "description": "Algorithm consistently favored certain demographics...",
    "severity": "Medium",
    "reported_at": "2025-03-15T10:00:00Z"
  },
  {
    "id": 2,
    "title": "LLM Hallucination in Critical Info",
    "description": "LLM provided incorrect safety procedure information...",
    "severity": "High",
    "reported_at": "2025-04-01T14:30:00Z"
  },
  {
    "id": 3,
    "title": "Minor Data Leak via Chatbot",
    "description": "Chatbot inadvertently exposed non-sensitive user metadata...",
    "severity": "Low",
    "reported_at": "2025-03-20T09:15:00Z"
  }
]



# Quick Summary

| Step | Command |
|:-----|:--------|
| Clone repo | `git clone <repo-link>` |
| Enter folder | `cd ai-safety-dashboard` |
| Install dependencies | `npm install` |
| Run project | `npm run dev` |
