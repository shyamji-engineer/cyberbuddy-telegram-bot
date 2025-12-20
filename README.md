# 🤖 CyberBuddy – AI Telegram Bot

CyberBuddy is a Python-based Telegram bot that works as your personal  
**cyber & tech assistant**.  
This bot uses both **OpenAI GPT** and **Google Gemini** APIs.

---

## ✨ Features

- 💬 AI chat (GPT + Gemini)
- 🧠 Conversation memory
- 🔄 Switch between AI models
- 📂 Read PDF, PPTX, and Excel files
- 📝 Create PDF files
- 🤖 Always introduces itself as **CyberBuddy**

---

## 🛠 Tech Stack

- Python 3.10+
- python-telegram-bot
- OpenAI API
- Google Gemini API
- PyPDF2, python-pptx
- pandas, openpyxl
- reportlab

---

## 📂 Project Structure

```text
.
├── cyberbuddy_bot.py
├── README.md
├── .gitignore
```

---

## ⚙️ Installation Guide (Full)

### 1️⃣ Clone Repository

```bash
git clone https://github.com/shyamji-engineer/cyberbuddy-telegram-bo.git
cd cyberbuddy-telegram-bo
```

### 2️⃣ Create Virtual Environment (Recommended)

**For Linux:**

```bash
python3 -m venv venv
source venv/bin/activate
```

**For Windows:**

```powershell
venv\Scripts\activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install python-telegram-bot openai google-generativeai \
            PyPDF2 python-pptx pandas openpyxl reportlab
```

---

## 🔑 API Keys Setup

To run CyberBuddy, you need 3 API keys:

### 🤖 Telegram Bot Token

- Open Telegram → search for **@BotFather**  
- Run the `/newbot` command  
- Copy the token

### 🧠 OpenAI API Key

- Visit: https://platform.openai.com/api-keys  
- Generate a new secret key

### 🌐 Google Gemini API Key

- Visit: https://makersuite.google.com/app/apikey  
- Generate an API key

---

## 🧪 Set Environment Variables

### Linux / Mac:

```bash
export TELEGRAM_BOT_TOKEN="your_telegram_bot_token_here"
export OPENAI_API_KEY="your_openai_api_key_here"
export GEMINI_API_KEY="your_gemini_api_key_here"
```

### Windows (PowerShell):

```powershell
setx TELEGRAM_BOT_TOKEN "your_telegram_bot_token_here"
setx OPENAI_API_KEY "your_openai_api_key_here"
setx GEMINI_API_KEY "your_gemini_api_key_here"
```

---

## ▶️ Run / Start Bot

```bash
python cyberbuddy_bot.py
```

If everything is correct, you will see:

```
🤖 CyberBuddy with memory + GPT + Gemini is running...
```

---

## 📲 Telegram Commands (How to Use)

- `/start`
- `/use gpt`
- `/use gemini`
- `/reset`
- `/makepdf <text>`

---

## 💬 Chat Example

```
Hi CyberBuddy
What is SQL injection?
```

---

## 🧠 Memory Example

```
My name is Shyam.
Do you remember my name?
```
