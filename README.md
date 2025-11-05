# langchain

Notebook collection exploring LangChain patterns, prompt engineering, chains/agents, and retrieval-augmented generation (RAG).

Purpose
- Educational notebooks that demonstrate prompt templates, simple chains, using vector stores, and integrating LLM providers.

Common notebooks (add / update as you add files)
- Prompt design examples
- Chains & agents demos
- RAG using local documents + FAISS/Chroma
- Small integrations (OpenAI or other LLM providers)

Quickstart

1. Clone
   git clone https://github.com/jumanewton/langchain.git
   cd langchain

2. Create environment
   python3 -m venv .venv
   source .venv/bin/activate

3. Install dependencies
   pip install -r requirements.txt
   Set API keys as env vars (OPENAI_API_KEY, etc.) or use a local LLM.

4. Run
   jupyter lab
   Open notebooks and follow top-cell instructions (most notebooks list expected env vars or sample data).

Security & Cost
- Do not commit API keys.
- Prefer small models or local embeddings for development to reduce cost.

Suggestions
- Add a .env.example listing expected env vars
- Add a short note per notebook describing inputs/outputs and which cells to run first
