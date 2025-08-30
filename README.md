# premier-league-prediction
A PL Prediction Model

# Premier League Prediction

## Project structure
```
premier-league-prediction/
├─ backend/
│  └─ main.py
├─ frontend/
│  └─ vite.config.ts
├─ README.md
├─ .gitignore
```

## Backend
- Stack: FastAPI + Uvicorn
- Run:
  - source .venv/bin/activate
  - uvicorn backend.main:app --reload
- Test:
  - pytest

## Frontend
- Stack: Vite + React + TypeScript
- Run:
  - cd frontend
  - npm install
  - npm run dev

## Development
- Use the project virtualenv: `.venv`
- Commit cleanly:
  - Python: format with black/ruff (optional), tests pass
  - Frontend: prettier/eslint (optional)
