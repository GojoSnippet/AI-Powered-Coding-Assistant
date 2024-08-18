# AstraAI

AstraAI is a small AI coding assistant I built to learn how large language models can help generate and understand code.  
It’s a basic full-stack project where you can type a prompt like  
“create a FastAPI route for user login”  
and it generates the code with explanations.

---

## Overview

The project has a FastAPI backend, a React frontend, and an AI layer that connects to language models.  
It also uses a vector database to remember context between messages so conversations feel continuous.  
Everything runs locally and can be deployed using Docker.

---

## Features

- Generate backend or frontend code from plain text  
- Explain existing code in simple terms  
- Store and recall previous prompts using embeddings  
- Works with both online and local models  
- Runs fully offline if needed  
- Simple chat interface for interaction  

---

## Tech Stack

- **Frontend:** React, TypeScript  
- **Backend:** FastAPI, Python  
- **Database:** PostgreSQL  
- **AI Layer:** LangChain, FAISS  
- **Other Tools:** Redis, Docker, WebSockets  

---

## How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/GojoSnippet/astraai
   cd astraai


Start the backend

cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload


Start the frontend

cd ../frontend
npm install
npm start



What I Learned

How language models handle context and prompts

How to connect FastAPI with a React frontend

How vector databases improve response relevance

How to containerize and run everything locally with Docker

About

I’m Sai Kumar Domakonda, a student who likes working on AI-based tools, backend systems, and small developer utilities.
This project was mainly built to practice integrating LLMs with real applications and learn end-to-end system design
