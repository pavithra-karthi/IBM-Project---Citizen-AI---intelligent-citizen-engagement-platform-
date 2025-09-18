Sustainable Smart City Assistants

An AI-powered platform designed to help cities and residents become more eco-conscious and connected.
It uses real-time data + AI to optimize energy, water, and waste management, provide personalized eco-tips, and assist city officials with data-driven insights and policy summaries.


---

✨ Features

💬 Conversational Interface – Q&A system for citizens and officials.

📑 Policy Summarization – Simplifies government documents into easy-to-understand summaries.

📈 Resource Forecasting – Predicts future trends for energy, water, and waste consumption.

🌍 Eco-tip Generator – Provides personalized advice for sustainable living.

👥 Citizen Feedback Loop – Gathers public input to inform city planning.

⚠️ Anomaly Detection – Identifies issues in sensor data.

📂 Multimodal Input – Accepts text, PDFs, and CSV files for analysis.



---

🏗️ Architecture

The system is built with a modular architecture:

Frontend: Streamlit – interactive dashboards, chat, and feedback forms.

Backend: FastAPI – handles document processing, chat, eco-tips, and reports.

LLM: IBM Watsonx Granite – generates summaries, eco-tips, and natural language interactions.

Vector Database: Pinecone – enables semantic search across documents.

ML Modules: Scikit-learn – supports forecasting and anomaly detection.



---

⚙️ Setup Instructions

✅ Prerequisites

Python 3.9+

pip and venv

API keys for:

IBM Watsonx

Pinecone


Internet access


🚀 Installation

# Clone repository
git clone https://github.com/your-username/sustainable-smart-city-assistants.git
cd sustainable-smart-city-assistants

# Create virtual environment
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

# Install dependencies
pip install -r requirements.txt

🔑 Configuration

Add your IBM Watsonx API key and Pinecone API key to an .env file:


WATSONX_API_KEY=your_watsonx_key
PINECONE_API_KEY=your_pinecone_key

▶️ Run Application

# Start backend
uvicorn app.main:app --reload

# Start frontend
streamlit run frontend/app.py


---

📌 Future Enhancements

Integration with IoT sensors for real-time urban monitoring.

Multi-language support for wider accessibility.

AI-powered policy recommendation system.

Mobile-first UI with offline support.
