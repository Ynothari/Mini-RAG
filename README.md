# 📚 Mini-RAG: Retrieval Augmented Engine

The **Retrieval Augmented Generation (RAG)** engine is a powerful application for document retrieval, summarization, and interactive question-answering. Built with **LangChain**, **Streamlit**, and **Pinecone**, this project offers a seamless web interface to interact with your documents in a conversational manner.

With Mini-RAG, you can upload multiple PDF files, generate vector embeddings, and ask natural language questions. Chat history is preserved, providing a smooth and interactive user experience.

---

## 🚀 Features

- **Streamlit Web App**  
  Clean, intuitive UI built using Streamlit for seamless interaction.

- **Secure API Key Inputs**  
  Easily input OpenAI and Pinecone credentials via sidebar or secrets file.

- **Multi-PDF Upload**  
  Upload and analyze multiple PDF documents simultaneously.

- **Smart Document Chunking**  
  Splits large documents into manageable text chunks, suitable for model token limits.

- **Vector Embeddings**  
  Transforms chunks into vector representations for accurate retrieval and Q&A.

- **Flexible Storage Options**  
  Choose between Pinecone or a local vector store for embedding storage.

- **Conversational Q&A**  
  Engage in dynamic, context-aware conversations with your documents.

- **Persistent Chat History**  
  Keeps track of past interactions for a richer user experience.

---

## 🛠️ Prerequisites

Ensure the following are installed/configured before running the app:

- Python 3.7+
- [LangChain](https://python.langchain.com/)
- [Streamlit](https://streamlit.io/)
- [Pinecone](https://www.pinecone.io/)
- OpenAI API key
- PDF documents to analyze

---

## 📦 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ynothari/Mini-RAG.git
   cd Mini-RAG

2. Install the required dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run src/rag_engine.py
   ```

4. **Open the App**  
   Launch the app in your browser by navigating to the local URL displayed in the terminal after running the Streamlit command.

5. **Provide Your Credentials**  
   Enter the following in the sidebar:
   - **OpenAI API Key**
   - **Pinecone API Key**
   - **Pinecone Environment**
   - **Pinecone Index Name**  
   
   Alternatively, you can store these in a `.streamlit/secrets.toml` file for convenience and security.

6. **Upload PDF Documents**  
   Use the built-in uploader to select and upload one or more PDF files for analysis.

7. **Process Documents**  
   Click the **"Submit Documents"** button to split the PDFs, generate vector embeddings, and store them accordingly.

8. **Start Chatting!**  
   Ask questions in natural language and receive contextual answers powered by the embedded document data. The chat remembers your history for a better experience.

---

## 📬 Contact

Have questions, suggestions, or want to collaborate? Feel free to reach out!

- 📧 [Email](mailto:awmhari007@gmail.com)  
- 💼 [LinkedIn](https://www.linkedin.com/in/ynothari/)

I'm open to collaboration and would be happy to connect!

