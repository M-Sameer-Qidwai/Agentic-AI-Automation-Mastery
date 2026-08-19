🎓 AI-Powered University Admission & Career Counselor

An AI-powered university counseling system that uses RAG, AI Agents, conversational memory, and workflow automation to answer student queries and automate admission-related assistance.

🚀 Features

* 📚 RAG-based Knowledge Base — Retrieves information from university PDFs using Pinecone.
* 🧠 AI Counselor Agent — Generates context-aware answers using OpenAI.
* 💬 Conversation Memory — Stores and retrieves chat history using Supabase.
* 📧 Email Automation — Detects email requests and automatically sends requested information through Gmail.
* 🔄 End-to-End Automation — Complete workflow orchestrated through n8n.
* 🌐 Webhook Integration — Connects the AI counselor with a web application.

🛠️ Tech Stack

n8n • OpenAI • Pinecone • Supabase • Gmail • RAG • AI Agents • Webhooks

🔄 Workflow

University PDFs
      ↓
OpenAI Embeddings
      ↓
Pinecone Knowledge Base
Student Query
      ↓
n8n Webhook
      ↓
Chat History + RAG Retrieval
      ↓
AI Counselor Agent
      ↓
Intent Detection
   ↙        ↘
Reply      Email
      ↓
Supabase
      ↓
Web Response

🎯 What I Built

This project goes beyond a basic chatbot by combining:

RAG + AI Agents + Memory + Intent Detection + Automation

The goal was to build a practical AI system that can retrieve information, understand student queries, maintain context, and take automated actions.

🙌 Acknowledgements

Special thanks to Farzeen and The Techzeen for the guidance and learning opportunity throughout this project.


Built by Muhammad Sameer Qidwai
Computer Science Student | AI & Automation
