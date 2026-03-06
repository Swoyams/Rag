RAGBOT
A lightweight Retrieval-Augmented Generation (RAG) chatbot designed for Google Colab. It fetches documents from Wikipedia and arXiv, then uses hybrid search (FAISS + BM25) and OpenAI's gpt-4o-mini to answer questions strictly based on the gathered context.

-Tech Stack
LangChain, OpenAI (gpt-4o-mini, text-embedding-3-small), FAISS, BM25, and Gradio.

-Quick Start
Set your API Key: In your Colab notebook, click the 🔑 Secrets icon in the left sidebar. Create a new secret named OPENAI_API_KEY, paste your key, and enable notebook access.
Run All Cells: The script will automatically install dependencies, load the documents, build the hybrid search database, and launch the Gradio chat UI.
Chat: Use the web interface to ask questions about the loaded documents!

Customization
To change the knowledge base topic, simply update the TOPIC variable at the top of the script:
