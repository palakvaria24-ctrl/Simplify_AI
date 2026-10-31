# 🧠 Complex Topic Simplifier

An AI-powered web application that transforms complex topics into simple, easy-to-understand explanations. It helps students and learners understand difficult concepts through clear, beginner-friendly language.

## 🚀 Project Overview

Complex Topic Simplifier is designed to make learning easier by using Artificial Intelligence (AI) to simplify complicated information.

Users can enter a topic or a difficult concept, and the application generates an easy-to-understand explanation.

The goal is to make complex knowledge more accessible, understandable, and useful for everyone.

## ✨ Features

- **AI-Powered Simplification:** Uses AI to convert complicated topics into simpler explanations.
- **Beginner-Friendly Language:** Presents information in clear and understandable language.
- **Interactive Web Interface:** Provides a user-friendly platform for entering topics and viewing explanations.
- **Fast Responses:** Generates explanations through an AI-powered backend.
- **Modern Frontend:** Built with React and Vite.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend development |
| FastAPI | Backend API framework |
| Groq API | AI-powered responses |
| React | Frontend development |
| Vite | Frontend development server and build tool |
| JavaScript | Frontend functionality |
| HTML & CSS | Web structure and styling |

## 📁 Project Structure

```text
SimplifyAI/
│
├── backend/
│   ├── main.py
│   ├── llm.py
│   ├── prompts.py
│   │
│   └── frontend/
│       ├── src/
│       ├── tests/
│       ├── index.html
│       ├── package.json
│       ├── package-lock.json
│       └── vite.config.js
│
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Complex-Topic-Simplifier
```

### 2. Set Up the Python Backend

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
.\venv\Scripts\Activate.ps1
```

Install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Configure the API Key

Create a `.env` file in the main project directory.

Add your Groq API key:

```env
GROQ_API_KEY=your_groq_api_key_here
```

Replace the placeholder with your own API key. Never share or upload your actual API key publicly.

### 4. Start the Backend

From the main project directory, run:

```bash
uvicorn backend.main:app --reload
```

### 5. Set Up the Frontend

Open a second terminal:

```bash
cd backend/frontend
```

Install frontend dependencies:

```bash
npm install
```

Start the frontend:

```bash
npm run dev
```

Open the local URL displayed in the terminal (usually `http://localhost:5173`).

## 🔐 Environment Variables

The application requires a Groq API key.

| Variable       | Description                           |
|---             |---                                    |
| `GROQ_API_KEY` | API key used for AI-powered responses |

Keep your `.env` file private. The `.env.example` file provides a template for configuration.

## 🎯 Project Objective

The primary objective of this project is to simplify complex educational and technical concepts using Artificial Intelligence, making learning more accessible and effective for students and other users.

## 🔮 Future Enhancements

- Support for additional AI models.
- More explanation styles and difficulty levels.
- Text-to-speech functionality.
- Support for multiple languages.
- Improved learning and user interaction features.

## 👩‍💻 Author

Developed as an AI-based web application project.

---

**Complex Topic Simplifier – Making Complex Learning Simple!**
