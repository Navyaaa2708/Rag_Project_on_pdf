# RAG Project on PDF

This project demonstrates the use of **Retrieval-Augmented Generation (RAG)** on PDF documents.  
The notebook implements a pipeline to process PDF files, retrieve relevant information, and generate responses using language models.

## 📂 Project Contents
- `RAG_project_on_pdf.ipynb` – Jupyter Notebook containing the full implementation.

## 🚀 Features
- PDF text extraction and preprocessing  
- Embedding generation for document chunks  
- Semantic search using vector similarity  
- Answer generation with context retrieved from the PDF  

## 🛠️ Requirements
To run this notebook, you will need:
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Required libraries:
  - `langchain`
  - `pandas`
  - `numpy`
  - `sentence-transformers`
  - `faiss-cpu`
  - `pypdf`
  - `transformers`
  - `google-generativeai` (if using Gemini API)

Install dependencies:
```bash
pip install pandas numpy sentence-transformers faiss-cpu pypdf transformers google-generativeai
```

## 📖 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/USERNAME/RAG_project_on_pdf.git
   cd RAG_project_on_pdf
   ```
2. Open the notebook:
   ```bash
   jupyter notebook RAG_project_on_pdf.ipynb
   ```
3. Run the cells step by step to process your PDF and generate responses.

## 📌 Notes
- Replace `USERNAME` with your GitHub username in the clone command.
- You can modify the notebook to work with your own PDFs and language models.

---
🔹 *This project is for learning and experimentation with RAG pipelines on PDF documents.*
