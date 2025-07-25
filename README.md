# Basic RAG System

This repository contains a **bare minimum Retrieval-Augmented Generation (RAG)** application using:

- LangChain
- OpenAI API
- In-memory vector store
- OpenAI Embedding model

It can load and extract PDF files, and is capable of performing question-answering and chat-based interactions using OpenAI models, grounded strictly in the content of the uploaded PDF files.

## 🖥️ Streamlit UI

The application features a [Streamlit](https://streamlit.io/) user interface to streamline the process:

- Enter your **OpenAI API key**
- Upload a **PDF file**
- Click to process the file
- Once processed, you can chat with the bot — it responds based on the contents of the PDF only

---

## 🚀 How to Run

1. **Clone this repository**

2. **Create a `.env` file** in the project root and add your OpenAI API key:
OPENAI_API_KEY=your-api-key-here

bash
Copy
Edit

3. **Create and activate a virtual environment**:
`python -m venv venv`
`source venv/bin/activate`  # On Windows use `venv\Scripts\activate`
Install the required dependencies:


`pip install -r requirements.txt`
Run the Streamlit app:


`streamlit run app.py`
Your browser will open the Streamlit UI for interaction.

# ⚠️ Notes
Most of the code is AI-generated to speed up prototyping and development.

This is a demo version created to teach NLP students at an Ontario college.

There will be no maintenance or version updates for this repository.

You are encouraged to download, modify, and extend the code to suit your needs.

# 📄 License
This project is released for educational and demonstration purposes only. No license, warranty, or ongoing support is provided.
