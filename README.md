# 💪 Fitness Buddy - Your AI Fitness Coach

**Problem Statement No.13** - Fitness Buddy
Project Details
Internship: Edunet Foundation IBM 4-Week Internship
Technology: LangFlow + IBM watsonx.ai + Meta Llama on IBM Cloud
Problem Statement
Fitness Buddy The challenge - In today’s fast-paced world, many individuals struggle to maintain a healthy lifestyle due to lack of personalized guidance, time constraints, and inconsistent motivation. Traditional fitness solutions often require expensive subscriptions, in-person consultations, or rigid schedules that don't adapt to personal preferences or daily routines. There is a growing need for an accessible, friendly, and intelligent virtual assistant that can provide on demand fitness advice, healthy lifestyle suggestions, and basic nutrition guidance—all tailored to individual needs and available at any time. Fitness Buddy aims to solve this problem by offering a conversational, AI-powered health and fitness coach that can: Recommend home workouts and routines based on user input. • Provide motivational tips and daily fitness inspiration. • Suggest simple, nutritious meal ideas. • Encourage habit-building and consistency.

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
