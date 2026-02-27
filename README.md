Customer Support GenAI Assistant

An intelligent AI powered customer support chatbot built using a Large Language Model that understands user queries and generates accurate, contextual responses in real time.

Overview

This project demonstrates how Generative AI can automate customer support interactions. The system accepts user queries, processes them using an LLM API, and returns human like responses similar to a real support agent.

It highlights practical skills in prompt engineering, API integration, and conversational AI system design.

Features

Natural language query understanding

Context aware responses

Real time interaction

LLM API integration

Modular and extendable design

Secure API key handling using environment variables

Tech Stack

Python
Groq LLM API
Jupyter Notebook
python dotenv

Project Structure

Customer-Support-GenAI
│
├── Customer_Support_Agent_GENAI.ipynb
├── README.md
├── requirements.txt
└── .gitignore

Installation

Clone the repository:

git clone https://github.com/harshinigorinta/customer-support-genai.git

cd customer-support-genai

Install dependencies:

pip install -r requirements.txt

Environment Setup

Create a .env file in the project root and add your API key:

GROQ_API_KEY=your_api_key_here

Do not upload this file to GitHub.

Running the Project

Start Jupyter Notebook:

jupyter notebook

Open the notebook file and run all cells to interact with the chatbot.

Example Interaction

User: How can I reset my password?

Assistant: To reset your password, go to the login page and click Forgot Password, then follow the instructions sent to your email.

Learning Outcomes

Working with LLM APIs
Designing prompt logic
Handling environment variables securely
Structuring AI projects professionally

Future Improvements

Convert notebook into FastAPI backend
Add chat interface UI
Store conversation history
Deploy using Docker

