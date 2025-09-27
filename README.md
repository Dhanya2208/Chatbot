# Chatbot
This project is an interactive AI-powered chatbot built using FastAPI as the backend, Streamlit as the user interface, and LangGraph to manage conversation flows. It integrates the Gemini API for advanced language generation, allowing the bot to understand and respond intelligently to user queries

# ✨ Gemini Chatbot (LangGraph + FastAPI + Streamlit)

This project demonstrates how to build an AI chatbot using:

- 🧠 **LangGraph** for managing multi-turn conversations  
- 🤖 **Google Generative AI (Gemini)** as the LLM backend  
- ⚡ **FastAPI** as the backend service  
- 💻 **Streamlit** as the frontend UI  
- 🌐 **ngrok** to expose both services publicly from Google Colab  

---

## 🚀 Features

- 💬 Conversational chatbot powered by **Gemini 2.0 Flash Lite**  
- ⚡ FastAPI backend that maintains a **chat history** (`chat_history.json`)  
- 💻 Streamlit frontend for interactive chatting  
- 📥 Option to **download chat history** from Colab  
- ☁️ Runs fully inside **Google Colab** with public ngrok links  

---

## 📦 Installation

Run this in a Colab notebook cell to install dependencies:

```bash
!pip install -qU langchain_google_genai langgraph fastapi uvicorn nest-asyncio pyngrok streamlit requests

