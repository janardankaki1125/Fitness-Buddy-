# 💪 Fitness Buddy - Your AI Fitness Coach

**Problem Statement No.13** - Fitness Buddy

An intelligent conversational fitness assistant built with **Langflow** + **IBM Granite** (watsonx.ai).

## ✨ Features
- Personalized home workouts (beginner to advanced)
- Nutritious Indian-style meal suggestions
- Daily motivation & habit building tips
- RAG-powered accurate knowledge base
- Conversational memory (remembers previous chats)

## 🛠️ Technology Stack
- **Langflow** - Low-code Visual AI Flow Builder
- **IBM watsonx.ai + Granite** (`ibm/granite-3-2-8b-instruct`)
- IBM Embeddings
- RAG (Chroma Vector Store)
- Conversation Memory

## 🚀 How to Run Locally

1. Install Langflow:
   ```bash
   pip install langflow -U
2.Run Langflow:Bashlangflow run
3.Open your browser and go to: http://localhost:7860
4.Click Import button → Upload fitness_buddy_flow.json
5.Open the IBM watsonx.ai component and add your:
IBM API Key
Project ID


📁 Project Structure

fitness_buddy_flow.json → Main Langflow flow
knowledge/ → PDFs used for RAG (optional)
screenshots/ → Project screenshots

🎯 About the Project
This project was developed as a solution for Problem Statement No.13 using IBM Cloud Lite + IBM Granite (Mandatory).
