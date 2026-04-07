# AI Chatbot

An AI-powered chatbot application built using Node.js and OpenAI API, designed to provide real-time conversational responses through a simple web interface.

## 🚀 Overview

This project demonstrates a full-stack chatbot system with a backend API and a lightweight frontend. It integrates with OpenAI to generate intelligent responses based on user input.

## ✨ Features

* Real-time AI-generated responses
* REST API built with Express.js
* Simple and responsive frontend interface
* Secure API key handling using environment variables
* Lightweight and easy to run locally

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Frontend:** HTML, CSS, JavaScript
* **API:** OpenAI API

## 📂 Project Structure

```
├── server.js          # Backend server
├── index.html         # Frontend UI
├── package.json       # Dependencies and scripts
└── .env               # Environment variables (not included in repo)

## ⚙️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/AshwithaKottam/ai-chatbot.git
cd ai-chatbot
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file and add your OpenAI API key:

```bash
OPENAI_API_KEY=your_api_key_here
```

4. Run the application:

```bash
node server.js
```

5. Open your browser and visit:

```
http://localhost:3000
```

## 🔐 Environment Variables

* `OPENAI_API_KEY` – Required for accessing OpenAI services

## 📌 Future Improvements

* Add chat history support
* Improve UI/UX with modern frameworks
* Deploy application to cloud platforms (Vercel/Render)
* Add authentication and user sessions

## 👩‍💻 Author

Ashwitha Kottam
