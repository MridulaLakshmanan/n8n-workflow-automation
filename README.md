# n8n-workflow-automation
# 🤖 AI Agent Workflow using n8n

## 📌 Overview
This project is my **first workflow automation built using n8n**.  
It demonstrates how an **AI Agent** can interact with users in real time and intelligently decide when to use external tools such as a **calculator** or a **weather API**, while also maintaining **conversation memory**.

The workflow is triggered by a chat message and routes the input through an AI Agent powered by a **Groq chat model**, enabling context-aware and tool-augmented responses.

---

## 🧠 What This Workflow Does
- Accepts user input through a **chat trigger**
- Processes the message using an **AI Agent**
- Uses:
  - Large Language Model (LLM) reasoning
  - Memory to retain conversational context
  - External tools to answer factual or computational queries
- Returns intelligent and structured responses to the user

---

## 🧩 Workflow Architecture

### Nodes Used
- **When Chat Message Received** – Triggers the workflow on user input
- **AI Agent** – Core reasoning engine that decides how to respond
- **Groq Chat Model** – LLM used for fast and efficient inference
- **Simple Memory** – Maintains conversation context
- **OpenWeatherMap Tool** – Fetches real-time weather information
- **Calculator Tool** – Performs mathematical computations

---
<img width="1470" height="842" alt="Screenshot 2026-02-01 at 8 24 22 PM" src="https://github.com/user-attachments/assets/c181b373-2c50-49fc-8f95-555831e873c3" />

## 🔧 Tools & Technologies
- **n8n** – Workflow automation platform
- **Groq LLM** – AI chat model integration
- **OpenWeatherMap API** – Real-time weather data
- **Calculator Tool** – Arithmetic operations
- **Memory Module** – Context persistence for conversations

---

## 🧠 Example Use Cases
- Ask general questions and receive AI-generated responses  
- Get real-time weather updates  
  - Example: *"What’s the weather in Chennai?"*
- Perform calculations  
  - Example: *"What is 245 × 37?"*
- Have multi-turn conversations with memory retention

---

## 🚀 How to Use This Workflow

1. Clone this repository
2. Open your **n8n instance**
3. Import the workflow:
   - Click **Import from file**
   - Select the provided `.json` workflow file
4. Configure the required credentials
5. Activate the workflow
6. Start chatting 🚀

---
<img width="1470" height="838" alt="Screenshot 2026-02-01 at 8 31 53 PM" src="https://github.com/user-attachments/assets/5fb8f119-cfe4-48fa-b6c1-72b3af9b84fd" />


## ⚠️ Credentials Notice
⚠️ **Credentials are not included.**  
Please configure them in your local n8n instance.

You will need to set up:
- Groq API credentials
- OpenWeatherMap API key

---


