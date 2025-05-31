
# 🤖 AI Chatbot with Qwen 2.5 & Ollama

This project demonstrates how to build and deploy an AI-powered chatbot **entirely locally** using:
- 🧠 **Qwen 2.5** — a multilingual LLM by Alibaba Cloud, optimized for reasoning and code generation.
- ⚙️ **Ollama** — an open-source runtime for running LLMs on your local machine.
- 🔧 **FastAPI** — lightweight backend server.
- 💬 **React.js** — dynamic frontend UI for chat.

---

## 🚀 Features

- Run AI locally with **no cloud dependencies**
- Preserve **data privacy**
- Avoid **API costs**
- Fast and lightweight local deployment

---

## 🧰 Technologies Used

- Qwen 2.5 (via Ollama)
- Ollama CLI
- Python 3.10+
- FastAPI
- React.js

---

## 📦 Requirements

Make sure you have the following installed:

```bash
ollama --version
python --version
node -v
npm -v
```

---

## 🔧 Backend Setup (FastAPI)

1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2. Run backend:
    ```bash
    uvicorn app.main:app --reload
    ```

---

## 💻 Frontend Setup (React)

1. Navigate to the `frontend/` directory.
2. Install dependencies:
    ```bash
    npm install
    ```

3. Run frontend:
    ```bash
    npm start
    ```

---

## ⚡ Running Qwen 2.5 with Ollama

1. Install Ollama: [https://ollama.com](https://ollama.com)
2. Pull Qwen model:
    ```bash
    ollama pull qwen:2.5
    ```
3. Run model:
    ```bash
    ollama run qwen:2.5
    ```

---
## 📸 Preview
Friendly AI chatbot. Respond in a conversational and engaging manner.
<img width="820" alt="Qwen_Chatbot" src="https://github.com/user-attachments/assets/857da556-7753-4c58-98b0-0c82afeb5cb7" />


---

## 📎 Notes

Check the course notes for a detailed breakdown of the course material.

[Here](https://github.com/RiddhiAiran/AI-Chatbot-qwen2.5/blob/main/Qwen%202.5.pdf)

---

## 🧠 Credits

Course: *AI Development with Qwen 2.5 and Ollama*  
Instructor: Vivan Arahana  
Notes by: Riddhi Airan

---
