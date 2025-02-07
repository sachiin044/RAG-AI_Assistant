# RAG-PaperBot: AI-Powered Research Assistant 🤖📄  

## 📝 Overview  
**RAG-PaperBot** is a **Retrieval-Augmented Generation (RAG)** system that enables users to ask questions about research papers and receive **AI-powered answers**. It integrates **Groq, OpenAI, FAISS**, and **LangChain** to retrieve relevant document chunks and generate responses.  

## 🚀 Features  
  ✅ Uses **LangChain** for seamless integration with LLMs  
  ✅ Supports **Groq API** for efficient question answering  
  ✅ Retrieves document chunks using **FAISS** vector embeddings  
  ✅ Handles **PDF research papers** for domain-specific Q&A  
  ✅ Powered by **Streamlit** for an interactive UI  

## 🛠️ Installation  
  ```bash
  git clone https://github.com/YOUR_GITHUB_USERNAME/RAG-PaperBot.git  
  cd RAG-PaperBot  
  pip install -r requirements.txt
  ```

## 📌 Setup & Execution

### 1️⃣ Set up API keys in a .env file:
  ```sh
  OPENAI_API_KEY=your_openai_api_key  
  GROQ_API_KEY=your_groq_api_key  
  HF_TOKEN=your_huggingface_token
  ```

### 2️⃣ Run the app:
  ```sh
  streamlit run app.py
  ````

### 3️⃣ Upload your research papers and enter your queries.

# 🏆 Tech Stack
  🔹 LangChain – LLM integration<br>
  🔹 FAISS – Vector database for efficient retrieval <br>
  🔹 OpenAI / Groq API – LLM-based question answering <br>
  🔹 Hugging Face Embeddings – Document vectorization <br>
  🔹 Streamlit – Interactive web UI <br>
  🔹 pypdf – PDF processing <br>

# 💡 Example Queries
- "Summarize the key findings of this paper." <br>
- "Explain the transformer model mentioned in the document." <br>
- "What are the contributions of this research?"

# 🔮 Future Enhancements
  🚀 Support for multiple document formats (TXT, DOCX) <br>
  🚀 Improved retrieval with ChromaDB <br>
  🚀 Enhanced UI for better user experience <br>

# 📜 License
  MIT License – Free to use and modify! 

If this project helps you—awesome! 🎉 If it crashes… well, let’s call it an undocumented feature. 🚀🔥 <br>
Feel free to contribute, report bugs, or just stare at the code in awe (or confusion). Either way, happy coding! 😎💻
  


