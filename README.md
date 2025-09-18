Sustainable Smart City Assistants
​Project Overview
​The "Sustainable Smart City Assistants" project is an AI-powered platform designed to help cities and their residents become more eco-conscious and connected. [cite_start]It uses a combination of real-time data and artificial intelligence to optimize resource management (energy, water, waste), provide personalized eco-tips, and assist city officials with data-driven insights and policy summaries.  
Features
​This application includes a range of features to support both citizens and city officials:
​[cite_start]Conversational Interface: A Q&A system for citizens and officials to interact with the AI.  
​[cite_start]Policy Summarization: Simplifies government documents into easy-to-understand summaries.  
​[cite_start]Resource Forecasting: Predicts future trends for energy, water, and waste consumption.  
​[cite_start]Eco-tip Generator: Provides personalized advice for sustainable living.  
​[cite_start]Citizen Feedback Loop: Gathers public input to inform city planning.  
​[cite_start]Anomaly Detection: Identifies issues in sensor data.  
​[cite_start]Multimodal Input: Accepts text, PDFs, and CSV files for analysis.  
Architecture
The project is built with a modular architecture:
[cite_start]Frontend: A user interface created with Streamlit for interactive dashboards, chat, and feedback forms.  
[cite_start]Backend: An API built with FastAPI to handle requests for document processing, chat, eco-tips, and reports.  
[cite_start]LLM: The core of the AI is the IBM Watsonx Granite Large Language Model, used for generating summaries, eco-tips, and natural language interactions.  
[cite_start]Vector Database: Pinecone is used for efficient semantic search across documents.  
[cite_start]ML Modules: Scikit-learn is utilized for machine learning tasks like forecasting and anomaly detection.  
Setup Instructions
Prerequisites
Python 3.9+
pip and venv
API keys for IBM Watsonx and Pinecone
Internet access
