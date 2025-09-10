# 📚 AI Backend – RAG-based Study Assistant

A Retrieval-Augmented Generation (RAG)-based AI backend built to power a smart study tool. It can answer doubts using domain-specific material and generate MCQs from uploaded PDFs using OpenAI’s GPT models.

---

## 🧠 Key Highlights

- **Built with Retrieval-Augmented Generation (RAG)** architecture.
- **Uses Weaviate vector DB** for semantic chunk search.
- **Powered by OpenAI’s GPT-3.5 Turbo** for question answering and generation.

---

## ✨ Features

### 📄 Upload Study Material
Upload PDFs and extract structured study chunks automatically.

### 🧠 Vector-Based Retrieval
Chunks are stored in Weaviate for efficient topic or semantic search.

### ❓ Ask Doubts
Students can ask free-form questions, and the system retrieves relevant content and generates an LLM-based answer.

### 📝 Generate MCQs
Automatically generate 20 well-formatted MCQs for any topic using GPT and custom prompts.

### 📌 Topic-based Indexing
Each chunk is stored along with an auto-detected topic, enabling filtered search and quiz generation.

---

## 🧰 Tech Stack

| Layer      | Tools Used                      |
|------------|---------------------------------|
| Backend    | Node.js, TypeScript, Express    |
| AI/LLM     | OpenAI GPT-3.5 Turbo            |
| Vector DB  | Weaviate (Cloud Sandbox)        |
| Parsing    | pdf-parse                       |
| Database   | Prisma (PostgreSQL, optional)   |

---

## 🚀 How to Run This Repository

### ✅ Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [PostgreSQL](https://www.postgresql.org/) (optional, if using Prisma)
- [Weaviate Cloud Sandbox](https://console.semi.technology/) account
- OpenAI API key ([https://platform.openai.com/](https://platform.openai.com/))

---

### 🔑 Step 1 – Clone the repository

```bash
git clone https://github.com/yourusername/rag-study-assistant.git
cd rag-study-assistant
