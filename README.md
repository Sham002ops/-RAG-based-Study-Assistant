📚 AI Backend – RAG-based Study Assistant
A RAG-based AI backend built to power a smart study tool . It can answer doubts using domain-specific material and generate MCQs from uploaded PDFs using OpenAI’s GPT models.

🧠 Built with Retrieval-Augmented Generation (RAG) architecture
🔍 Uses Weaviate vector DB for semantic chunk search
🤖 Powered by OpenAI (gpt-3.5-turbo) for question answering and generation

✨ Features
📄 Upload Study Material
Upload PDFs and extract structured study chunks automatically.

🧠 Vector-Based Retrieval
Chunks are stored in Weaviate for efficient topic or semantic search.

❓ Ask Doubts
Students can ask free-form questions, and the system retrieves relevant content and generates an LLM-based answer.

📝 Generate MCQs
Automatically generate 20 well-formatted MCQs for any topic using GPT and custom prompts.

📌 Topic-based Indexing
Each chunk is stored along with an auto-detected topic, enabling filtered search and quiz generation.

🧰 Tech Stack

Layer	Tools Used
Backend    - Node.js, TypeScript, Express
AI/LLM     - OpenAI GPT-3.5 Turbo
Vector DB	 - Weaviate (Cloud Sandbox)
Parsing	   - pdf-parse
Database	 - Prisma (PostgreSQL, optional)
