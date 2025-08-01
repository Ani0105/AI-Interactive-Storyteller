
# AI Interactive Storyteller

**AI Interactive Storyteller** is a full-stack web application where users explore branching narratives driven by AI. Users engage in a “choose-your-own-adventure” format, with a dynamic backend managing state and story progression.

## 🔧 Tech Stack

- **Frontend:** React + Vite
- **Backend:** FastAPI + Python + SQLite
- **Communication:** REST API

## 🚀 How to Run This Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/AI-Interactive-Storyteller.git
cd AI-Interactive-Storyteller
```

### 2. Start the Backend (API)

```bash
cd api
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
uvicorn main:app --reload
```

API will be available at: `http://127.0.0.1:8000/docs`

---

### 3. Start the Frontend (Client)

```bash
cd ../client
npm install
npm run dev
```

Frontend will be live at: `http://localhost:5173`

