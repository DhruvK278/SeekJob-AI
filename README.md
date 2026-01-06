# 🚀 SeekJob-AI

**SeekJob-AI** is an autonomous AI-powered placement agent that automatically discovers, evaluates, and tracks job and internship opportunities.

> ⚠️ Status: Currently in development

---

## 💡 What it Does
- Runs automatically on a schedule (no manual input)
- Fetches job listings from external sources
- Normalizes job data into a standard format
- Uses AI reasoning to evaluate job relevance (planned)
- Notifies and tracks suitable opportunities (planned)

---

## 🛠 Tech Stack
- n8n (Workflow Automation)
- Docker (Containerization)
- AI / LLM APIs (planned)
- Kubernetes (planned)

---

## 🧩 Architecture
Cron Trigger → Job Fetch → Data Normalization → AI Decision → Actions

## 🐳 Run with Docker
```bash
docker run -it --rm --name n8n \
  -p 5678:5678 \
  -v n8n_data:/home/node/.n8n \
  docker.n8n.io/n8nio/n8n
```
---

## 🎯 Goal
Build a deployable, autonomous AI agent that simplifies job discovery and decision-making for students and fresh graduates.

---


### ✅ This is PERFECT for:
- GitHub
- Resume link
- Internship interviews

---



**Made by - Dhruv Kumar**
