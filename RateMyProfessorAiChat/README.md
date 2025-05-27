# 🧠 RateMyProfessor AI Chat

RateMyProfessor AI Chat is an intelligent chatbot that uses natural language processing (NLP) to summarize, interpret, and respond to RateMyProfessor.com reviews in a conversational format. Built to simplify the student decision-making process, it enables users to interact with professor reviews using human-friendly queries.

---

## 🚀 Why This Project?

Navigating dozens of scattered RateMyProfessor reviews can be tedious and overwhelming. This tool transforms that raw feedback into an intuitive Q&A experience — just ask a question, and get a synthesized response based on real student input.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask)
- **NLP Engine:** OpenAI API (GPT-4)
- **Web Scraping:** BeautifulSoup
- **Deployment:** (Optional) Render, Heroku, or Vercel

---

## ✨ Features

- 💬 **Conversational Interface** – Ask questions like “Is this professor lenient?” or “Do students like their teaching style?”
- 📊 **AI Summarization** – GPT-4 processes dozens of reviews and extracts meaningful insights
- 🔍 **Dynamic Web Scraping** – Scrapes live data from RateMyProfessor in real-time
- 🌐 **Lightweight Frontend** – Clean and responsive UI for instant interaction

---

## 📸 Demo

![Chat Demo](https://user-images.githubusercontent.com/yourusername/demo.gif)

> “Is Professor Smith tough on grading?”  
> _“Most students say Professor Smith is a fair grader with clear rubrics, though a few found the exams slightly challenging...”_

---

## 🧠 How It Works

1. **User enters a professor name + school**
2. **The app scrapes RateMyProfessor reviews**
3. **Reviews are sent to the OpenAI API for analysis**
4. **GPT returns a summary response**
5. **Response is rendered to the UI as natural dialogue**

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/SimpleHelloProgram/RateMyProfessorAiChat.git
cd RateMyProfessorAiChat

# Set up a virtual environment
python -m venv env
source env/bin/activate

# Install dependencies
pip install -r requirements.txt

# Add your OpenAI API key to .env
echo "OPENAI_API_KEY=your_key_here" > .env

# Run the server
python app.py

Then visit http://localhost:5000 in your browser.

#🛡️ Disclaimer
This project is for educational use only. It scrapes publicly available reviews and uses AI summarization but does not store or sell any personal data. Always respect RateMyProfessor’s terms of service.

#📌 Future Plans
🔐 Add user auth (JWT)

🧠 Improve review chunking + token management

📱 Mobile-friendly React frontend

🧪 Add feedback form for students to rate chatbot accuracy

📊 Visualization of review sentiment over time


