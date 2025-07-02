# 🧠 Semiconductor Manufacturing Chatbot (RAG + Text-to-SQL)

This project is a 1-week POC to build a Retrieval-Augmented Generation (RAG) chatbot that helps engineers and analysts interact with semiconductor manufacturing data using natural language.

## 🚀 Features

- ✅ Ingest structured (SQL) and unstructured (PDF) data
- ✅ Embed text into a vector database using FAISS
- ✅ Enable natural language SQL queries using OpenAI + LangChain
- ✅ Frontend chatbot built with Streamlit or FastAPI
- ✅ Azure/Databricks-ready design

---

## 🗂️ Project Structure

| Folder | Description |
|--------|-------------|
| `data/` | Sample CSVs and PDFs for ingestion |
| `ingestion/` | Scripts to parse, clean, and load data |
| `rag_pipeline/` | LLM + vector pipeline (LangChain agents) |
| `app/` | Frontend (Streamlit or FastAPI) chatbot |
| `notebooks/` | Jupyter/Databricks notebooks for exploration |
| `config/` | App-level configuration and secrets |

---

## 🧪 Example Questions to Ask

- "What was the wafer yield trend last month by tool?"
- "Summarize the causes of low yield from recent reports."
- "List the wafers with the most defect occurrences."
- "What shift had the highest rejection rate last week?"

---

## 🛠️ Setup Instructions

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/semiconductor-rag-assistant.git
   cd semiconductor-rag-assistant
