# RAG PDF Chatbot

A Retrieval-Augmented Generation (RAG) based chatbot that enables users to ask questions from PDF documents and receive context-aware answers using open-source models.

---

## 🚀 Overview

This project implements a complete RAG pipeline that:

* Loads and processes PDF documents
* Splits text into manageable chunks
* Converts text into vector embeddings
* Stores embeddings in a vector database
* Retrieves relevant context for queries
* Generates answers using a language model

The system is fully **free and does not rely on paid APIs**, making it suitable for academic and portfolio projects.

---

## 🧠 Features

* PDF document understanding
* Context-based question answering
* Vector search using ChromaDB
* Open-source embeddings (Sentence Transformers)
* Lightweight LLM (FLAN-T5)
* Interactive terminal-based chatbot
* No OpenAI API required

---

## 🛠️ Tech Stack

* LangChain
* ChromaDB
* HuggingFace Transformers
* Sentence Transformers
* Python

---

## 📂 Project Structure

```
rag-pdf-chatbot/
│
├── app.py              # Main application
├── requirements.txt   # Dependencies
├── README.md          # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the repository

```
git clone https://github.com/your-username/rag-pdf-chatbot.git
cd rag-pdf-chatbot
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Place your PDF file in the project folder and rename it:

```
sample.pdf
```

2. Run the application:

```
python app.py
```

3. Ask questions in the terminal:

```
Ask a question: What is the Transformer model?
```

4. Get answers based on the document context.

---

## 💡 Example

**Input:**

```
What is the Transformer model?
```

**Output:**

```
The Transformer is a neural network architecture based on self-attention mechanisms, commonly used for sequence modeling tasks such as machine translation.
```

---

## 🔍 How It Works

1. **Document Loading**
   PDF is loaded using a document loader.

2. **Text Splitting**
   Text is divided into smaller chunks for efficient processing.

3. **Embedding Generation**
   Each chunk is converted into vector embeddings.

4. **Vector Storage**
   Embeddings are stored in ChromaDB.

5. **Retrieval**
   Relevant chunks are retrieved based on user query.

6. **Answer Generation**
   Retrieved context is passed to the LLM to generate a response.

---

## ✅ Advantages

* No API cost
* Works offline after model download
* Easy to extend and customize
* Beginner-friendly architecture

---

## 🚀 Future Improvements

* Streamlit-based web UI
* Multi-document support
* Chat history
* Advanced models (Mistral / LLaMA)
* Deployment on cloud platforms

---

## 📌 Use Cases

* Academic research assistance
* Document-based Q&A systems
* Knowledge base chatbot
* Personal learning assistant

---

## 📄 Resume Description

Built a Retrieval-Augmented Generation (RAG) based chatbot using LangChain, ChromaDB, and HuggingFace models to enable context-aware question answering over PDF documents without relying on paid APIs.

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests.

---

## 📜 License

This project is open-source and available under the MIT License.
