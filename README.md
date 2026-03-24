# BCPT6SRM Project

## Overview

This project is a full-stack application consisting of a frontend (built with Vite + React + Tailwind) and a Python backend. It is designed to handle data processing, verification, and interaction between user interface and backend logic.

---

## Project Structure

```
BCPT6SRM-main/
│
├── src/                 # Frontend source code
├── public/              # Static assets
├── python_backend/      # Backend (Python)
│
├── index.html
├── package.json
├── package-lock.json
├── vite.config.ts
├── tailwind.config.ts
├── tsconfig.json
├── requirements.txt
├── README.md
```

---

## Features

* Modern frontend using React + Vite
* Styled with Tailwind CSS
* Python backend for processing and logic
* Modular and scalable structure

---

## Installation & Setup

### 1. Clone the repository

```
git clone <your-repo-link>
cd BCPT6SRM-main
```

---

### 2. Frontend Setup

```
npm install
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

---

### 3. Backend Setup

Create virtual environment:

```
python -m venv venv
source venv/bin/activate     # Linux/Mac
venv\Scripts\activate        # Windows
```

Install dependencies:

```
pip install -r requirements.txt
```

Run backend:

```
python app.py
```

---

## Configuration

* Ensure backend URL is correctly connected in frontend
* Update environment variables if needed (.env)

---

## Scripts

Frontend:

```
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview build
```

---

## Git Ignore (Recommended)

```
node_modules/
venv/
__pycache__/
*.pyc
.env
```

---

## Future Improvements

* Add authentication system
* Improve UI/UX
* Deploy using AWS / Vercel / Render

---

## Author

Mohith

---

## License

This project is for academic and learning purposes.
