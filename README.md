# 🚀 Chatbot Using LangGraph + Ollama (Gemma 3 1B)

<p align="center">
  <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="200"/>
</p>

<p align="center">
  <b>A Powerful AI Chatbot built with LangGraph, Streamlit & Ollama (Gemma 3 1B)</b>
</p>

---

## 🌟 Overview

This project is a **modular AI chatbot system** built using:

- 🧠 **LangGraph** for workflow orchestration  
- 🤖 **Ollama (Gemma 3:1B)** for local LLM inference  
- 🌐 **Streamlit** for interactive UI  
- 🗄️ **SQLite Database** for persistent memory  

It supports multiple chatbot types like:
- 💬 Basic Chatbot  
- 🛠️ Tool-enabled Chatbot  
- 🗂️ Database-integrated Chatbot  
- 📚 RAG (Retrieval-Augmented Generation) Chatbot  
- ⚡ Streaming Response Chatbot  

---

## 🎥 Demo Preview

<p align="center">
  <img src="https://media.giphy.com/media/coxQHKASG60HrHtvkt/giphy.gif" width="600"/>
</p>

---

## 🏗️ Project Structure

Chatbot-Using-LangGraph/
│
├── langgraph_backend.py
├── langgraph_tool_backend.py
├── langgraph_database_backend.py
├── langraph_rag_backend.py
│
├── streamlit_frontend.py
├── streamlit_frontend_tool.py
├── streamlit_frontend_database.py
├── streamlit_rag_frontend.py
├── streamlit_frontend_streaming.py
│
├── chatbot.db
├── requirements.txt
└── README.md

# ⚙️ Setup Guide
🔹 Clone Repository
git clone https://github.com/your-username/Chatbot-Using-LangGraph.git
cd Chatbot-Using-LangGraph
🔹 Create Virtual Environment
python -m venv venv
venv\Scripts\activate
🔹 Install Dependencies
pip install -r requirements.txt
🔹 Setup Ollama

👉 https://ollama.com

ollama pull gemma3:1b
ollama run gemma3:1b
🔧 Configure Ollama
from langchain_community.chat_models import ChatOllama

llm = ChatOllama(
    model="gemma3:1b",
    temperature=0.7
)
# ▶️ Run the Project

🔥 Streaming Chatbot (Best Experience)

streamlit run streamlit_frontend_streaming.py

💬 Basic Chatbot

streamlit run streamlit_frontend.py

🛠️ Tool Chatbot

streamlit run streamlit_frontend_tool.py

📚 RAG Chatbot

streamlit run streamlit_rag_frontend.py
🧩 Architecture Flow
User 💬
   ↓
Streamlit UI 🌐
   ↓
LangGraph ⚙️
   ↓
Ollama (Gemma 3 1B) 🤖
   ↓
Response ✅

# 📸 UI Glimpse

<p align="center"> <img src="https://media.giphy.com/media/l0HlBO7eyXzSZkJri/giphy.gif" width="500"/> </p>

# 🚀 Future Enhancements
🔍 PDF Chatbot (RAG)
🎤 Voice Assistant
🌐 Web Deployment
🧠 Fine-tuned Models
📊 Dashboard Analytics

# 🤝 Contributing
**fork → clone → branch → commit → push → PR 🚀**

# 📜 License
MIT License

# 👨‍💻 Author
**Somen Pradhan**
AI/ML Developer 

# ⭐ Support
If you Like this
**⭐ Star the Repo**
🍴 Fork It
📢 Share It

<p align="center"> <img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="200"/> </p>

# 🔥 Pro Tip
💡 Run locally with Ollama → No API cost + Full Privacy 🔐
---

If you want next level 🔥 I can upgrade this with:
- GitHub **badges (stars, forks, license, etc.)**
- A **banner image (custom design)**
- A **LinkedIn + resume project description**

Just tell me 👍
