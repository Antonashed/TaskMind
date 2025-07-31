# 🧠 TaskMind — AI-Powered Task Tracker Telegram Bot

TaskMind is a Telegram bot designed to help you quickly capture and manage tasks that come to mind during your daily routine. Powered by Llama 3, it understands natural language and voice input, classifies tasks by categories and deadlines, and keeps your life organized — even when you're on the go.

---

## 🚀 Features

### 📌 Core
- Add tasks via messages, natural phrases, or voice
- List tasks by category, date, or completion status
- Mark tasks as done or delete them
- Automatic deadline recognition (`"remind me tomorrow at 9 AM"`)
- Smart categorization and tagging using Llama 3

### 🔔 Reminders
- Deadlines and scheduled notifications
- `/today`, `/week`, `/next` commands to view upcoming tasks

### 🗂️ Organization
- Task categories (e.g., `Work`, `Personal`, `Learning`)
- Hashtag-style tags (e.g., `#urgent`, `#shopping`)

### 🎤 Voice & Natural Input
- Telegram voice message recognition → task creation
- Local transcription and parsing of speech via Whisper / Vosk (configurable)

### 📅 Calendar Integration
- Sync tasks with Google Calendar (OAuth2)
- Push notifications from calendar events

---

## 🛠 Tech Stack

- **Python 3.11+**
- **Aiogram 3** 
- **SQLAlchemy
- **Llama 3** 
- **FastAPI** 
- **Whisper**
- **Google Calendar API** 
- **Docker** 
- **Unit testing**

---

## 📦 Setup (Local)

1. **Clone the repo**
```bash
git clone https://github.com/yourusername/taskmind-bot.git
cd taskmind-bot
