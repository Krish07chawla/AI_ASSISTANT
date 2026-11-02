# 🤖 AI Assistant — Flask & OpenAI API

A web-based AI Assistant built using **Python, Flask, and the OpenAI API**. The application allows users to interact with an AI assistant through a simple web interface.

## 🚀 Features

- **AI-powered responses:** Uses the OpenAI API to generate responses to user questions.
- **Flask backend:** Handles HTTP requests and connects the frontend with the OpenAI API.
- **Interactive interface:** Simple frontend built with HTML and CSS.
- **Environment variables:** Uses `python-dotenv` to securely load API credentials.
- **Debug mode:** Flask development server for testing and development.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web framework |
| OpenAI API | AI-generated responses |
| HTML | Webpage structure |
| CSS | Frontend styling |
| python-dotenv | Environment variable management |

## 📁 Project Structure

```text
AI_ASSISTANT/
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── .env
└── main.py
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_PROJECT_FOLDER>
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Install dependencies

```bash
python -m pip install flask python-dotenv openai
```

### 4. Configure your API key

Create a `.env` file in the project root directory:

```env
OPENAI_API_KEY=your_openai_api_key
```

Replace `your_openai_api_key` with your actual API key.

### 5. Run the application

From the project root directory, execute:

```bash
python -m flask --app AI_ASSISTANT.main run --debug
```

### 6. Open in your browser

Visit:

```text
http://127.0.0.1:5000
```

## 🔐 Security

- Store API credentials in the `.env` file.
- Never upload your actual API key to GitHub.
- Add `.env` and `.venv/` to `.gitignore`.

## 📚 Learning Objectives

This project helps demonstrate practical knowledge of:

- Flask application development
- REST-style HTTP request handling
- OpenAI API integration
- Environment variable management
- Connecting frontend and backend
- Python virtual environments

## 👨‍💻 Future Improvements

- Add conversation history.
- Improve the chatbot interface.
- Add streaming responses.
- Implement user authentication.
- Deploy the application online.

---

**Built with Python, Flask & OpenAI API.**
