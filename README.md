# 🤖 AI RAG Automation Workflow using n8n + Google Gemini + Pinecone

This project automates a **Retrieval-Augmented Generation (RAG)** pipeline using **n8n**, integrating **Google Gemini**, **Pinecone**, and **Google Drive** to enable dynamic document ingestion and intelligent conversational AI responses.

<img width="1464" height="543" alt="image" src="https://github.com/user-attachments/assets/c20bd7b7-29fd-481e-b27a-b2acebb54e41" />




This workflow allows you to:
- Automatically **upload and embed new documents** from Google Drive into Pinecone.
- Use **Google Gemini API** to generate embeddings and chat responses.
- Manage a **memory buffer** for context-aware conversations.
- Run a **RAG-powered AI assistant** capable of referencing newly added documents in real time.



## ⚙️ Key Components

| Component | Description |
|------------|-------------|
| **n8n** | No-code automation platform used to orchestrate the entire pipeline. |
| **Google Drive Trigger** | Detects when a new file is uploaded to a specific folder. |
| **Document Loader** | Reads and loads documents for processing. |
| **Google Gemini Embeddings** | Generates vector embeddings for document chunks. |
| **Pinecone Vector Store** | Stores and retrieves document embeddings for semantic search. |
| **Google Gemini Chat Model** | Generates responses using RAG with real-time document retrieval. |
| **AI Agent Node** | Defines assistant behavior and integrates memory + tools. |
| **Memory Buffer** | Maintains recent chat history for contextual awareness. |

---

## 🧩 Workflow Highlights

- 📂 **Google Drive Automation:** Automatically detects new files and processes them.
- 🧠 **Gemini-Pinecone Integration:** Stores document embeddings for RAG queries.
- 💬 **Context-Aware AI Agent:** Uses vector retrieval + chat model to answer user queries.
- 🔁 **Continuous Learning Loop:** New documents enrich the assistant’s knowledge base dynamically.



## 🛠️ Technologies Used

- **n8n**
- **Google Gemini API (via LangChain nodes)**
- **Pinecone Vector Database**
- **LangChain Integration**
- **Google Drive API**



## 🧰 Use Cases

- Internal knowledge base automation
- AI assistants with live document updates
- Customer support bots with document grounding
- Intelligent automation for content-based Q&A systems









