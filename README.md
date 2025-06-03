# AI-medicobot

# 🩺 MedCareBot — AI Medical Chatbot with RAG, Hugging Face & LangChain

**MedCareBot** is an AI-powered medical chatbot that uses Retrieval-Augmented Generation (RAG) to answer disease-related queries based on trusted medical documents. It combines cutting-edge technologies like Hugging Face Transformers, LangChain, and semantic search to support healthcare professionals and patients with quick, contextual information — all wrapped in a clean Streamlit interface.

---

## 🌟 Key Features

- 💬 **Natural Language Medical Query Support**  
  Ask questions about diseases, symptoms, treatments, and get AI-generated responses with contextual accuracy.

- 🔍 **Retrieval-Augmented Generation (RAG)**  
  Enhances responses with real-time document retrieval from a local medical knowledge base.

- 📚 **PDF-based Knowledge Base**  
  Upload your own medical research PDFs — the bot will chunk, embed, and index them for semantic search.

- 🧠 **Powered by Hugging Face & LangChain**  
  Combines the best of NLP models and retrieval pipelines for powerful, grounded answers.

- 🖥️ **Built with Streamlit**  
  Lightweight, interactive UI for fast deployment and easy interaction.

---

## 📁 Project Structure

MedCareBot/
│
├── data/ # Folder for storing PDF knowledge base
├── embeddings/ # Stores vector database files
├── app.py # Streamlit frontend
├── ingest.py # PDF loading, chunking & embedding
├── config.py # Model and system settings
├── requirements.txt # Python dependencies
└── README.md # This file


---


## ⚙️ Installation

### 🔧 Prerequisites:
- Python 3.8+
- pip

### 📦 Setup Instructions:

```bash
# Clone the repo
git clone https://github.com/yourusername/MedCareBot.git
cd MedCareBot

# Install dependencies
pip install -r requirements.txt

# Add your PDFs to the /data folder

# Ingest and embed documents
python ingest.py

# Run the chatbot
streamlit run app.py

---



🛠️ Tech Stack
Tech	Role
🧠 Hugging Face	Transformer-based language models
🧱 FAISS	Vector search for semantic retrieval
🔗 LangChain	Orchestrating LLM + retrieval logic
📄 PyMuPDF	PDF reading and chunking
🌐 Streamlit	Interactive frontend for the chatbot
🗃️ Chroma/FAISS	Vector database backend

🎛️ Customization
Add your own PDFs to data/ and rerun ingest.py to expand the knowledge base.

Tune response behavior with temperature, top_k, or chunk_size in config.py.

🧪 Example Use Cases
Clinical query resolution (e.g., "What are the symptoms of dengue?")

Medical research assistant for students or professionals

Rapid disease information during teleconsultation

🤖 Demo Preview
Coming soon: [Live Demo Link] or add your own screenshots/gif here.

🧬 Future Enhancements
🏥 Integration with real-time medical APIs (e.g., WHO, CDC)

🧑‍⚕️ Doctor-mode with advanced query handling

🗣️ Speech-to-text interaction

📈 Chat history & feedback logging

📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

🙌 Acknowledgements
Monica's Tutorial

Hugging Face

LangChain

Streamlit

PyMuPDF

FAISS



💡 MedCareBot — Empowering better decisions through AI-driven medical insights.
