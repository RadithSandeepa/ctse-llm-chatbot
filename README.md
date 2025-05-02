# ctse-llm-chatbot
```
CTSE_Chatbot_Project/
│
├── 📓 CTSE_Chatbot.ipynb             # 🔹 Main Jupyter Notebook (final submission)
├── 📄 Report.pdf                     # 🔹 Justification Report (as required)
├── 📹 demo.mp4                       # 🔹 Video Demonstration (2–3 mins)
│
├── 📁 data/                          # 🔸 Raw input lecture materials
│   └── CTSE_Lecture_Notes.pdf
│
├── 📁 rag_utils/                     # 🔸 Optional Python helper functions
│   ├── pdf_loader.py                # Code to extract and clean text from PDFs
│   ├── chunker.py                   # Functions for text chunking
│   ├── vector_store.py              # Vector DB setup (FAISS/Chroma)
│   └── rag_chain.py                 # RAG chain construction
│
├── 📁 outputs/                       # 🔸 (Optional) Store intermediate files
│   ├── embeddings.faiss             # FAISS DB (if persisted)
│   └── logs/                        # Any logs or temp files
│
├── 📁 genai_prompts/                # 🔸 Store GenAI prompts & responses
│   ├── prompt1.txt
│   └── response1.txt
│
└── requirements.txt                 # 🔸 All dependencies (for reproducibility)
```
