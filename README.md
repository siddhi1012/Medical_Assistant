🩺 AI-Powered Medical Assistant
An AI-powered medical assistant that can answer health-related queries, suggest possible conditions, and provide nutritional advice.
It supports document upload (PDFs) and uses LLM-based retrieval with a vector database to give relevant answers.
Deployed on Streamlit Cloud for easy access.

🔗 Live Demo: medicalassistants.streamlit.app

📌 Features
💬 AI Chatbot for health-related questions.

📄 PDF Upload for extracting and searching document content.

🧠 LLM-powered responses using LangChain.

📂 Vector Search with Pinecone for quick retrieval.

🌐 FastAPI backend integration.

☁ Streamlit Cloud Deployment.

🛠️ Tech Stack
Frontend & UI: Streamlit

Backend API: FastAPI

LLM Framework: LangChain

Vector Database: Pinecone

Programming Language: Python

Deployment: Streamlit Cloud

📂 Project Structure
bash
Copy
Edit
medical-assistant/
│
├── app.py                  # Main Streamlit app
├── backend/
│   ├── api.py               # FastAPI backend
│   ├── utils.py              # Helper functions
│
├── requirements.txt         # Python dependencies
├── README.md                # Documentation
├── .gitignore               # Ignored files
└── assets/                  # Images, icons, etc.
⚙️ Installation & Setup
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/siddhi1012/medical-assistant.git
cd medical-assistant
2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Set Up Environment Variables
Create a .env or secrets.toml (for Streamlit Cloud) with:

ini
Copy
Edit
OPENAI_API_KEY=your_api_key
PINECONE_API_KEY=your_api_key
PINECONE_ENVIRONMENT=your_environment
4️⃣ Run Locally
bash
Copy
Edit
streamlit run app.py
🚀 Deployment on Streamlit Cloud
Push the repo to GitHub.

Go to share.streamlit.io.

Connect your GitHub repository.

Select app.py as the entry point.

Add your API keys in Secrets.

🖼️ Screenshots
Home Page	Chat Interface

🤝 Contributing
Pull requests are welcome!
Please open an issue first to discuss proposed changes.

📜 License
This project is licensed under the MIT License.


