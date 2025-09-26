# 🧠 Memory-Based Chatbot with RAG and Persistent Memory

A memory-enhanced chatbot leveraging **Retrieval-Augmented Generation (RAG)** and persistent vector memory using **FAISS**. This chatbot integrates **Euriai API** for embeddings and chat completions, allowing context-aware and personalized conversations that persist across sessions.

---

## Features

- **RAG (Retrieval-Augmented Generation):** Retrieves relevant past memories to improve response quality.
- **Persistent Memory:** Stores conversation history and embeddings in a FAISS vector store.
- **Conversation History:** Maintains a history of messages to create context-aware responses.
- **Custom Memories:** Users can add custom memory entries to the chatbot.
- **User Identity:** Personalizes responses based on the user’s identity.
- **LangChain Integration (Optional):** Supports advanced LLM workflows if `EuriaiLangChainLLM` is installed.
- **Streamlit UI:** Clean web interface with chat and sidebar controls for API key, identity, and memories.
- **Euriai API Integration:** Direct API calls for embeddings and chat completions.

---

## Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd <repo-folder>
```

2. Create a virtual environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate  # Linux / macOS
venv\Scripts\activate     # Windows
pip install -r requirements.txt
```

3. Create a `.env` file with your Euriai API key: 

```bash
EURIAI_API_KEY="your_api_key_here"
USER_IDENTITY="Your Name or Profile Info"
```
4. Run the chatbot using Streamlit:

```bash
streamlit run app.py
```
