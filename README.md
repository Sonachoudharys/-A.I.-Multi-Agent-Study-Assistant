# A.I. Multi-Agent Study Assistant

An autonomous multi-agent system designed to create, track, and adapt personalized study plans using modular AI agents.

## 🌟 Features
- Multi-agent architecture (Scheduler, Planner, Tracker, Recommender)
- Shared memory store for persistent context
- Plan adaptation for missed sessions
- Resource recommendation using search tools
- Evaluation metrics for plan quality
- Cloud Run deployment-ready Flask API

## 📂 Project Structure
AIMultiAgent-StudyAssistant/
│── notebook/
│   └── AIMultiAgent_StudyAssistant.ipynb
│── src/
│   ├── agents.py
│   ├── memory.py
│   ├── orchestrator.py
│   └── utils.py
│── deployment/
│   ├── Dockerfile
│   ├── app.py
│   └── requirements.txt
│── writeup.md
│── video_script.txt
│── slides.pdf
│── README.md

## 🚀 Installation
```bash
pip install -r deployment/requirements.txt
