# Generative AI Concepts & Applications

This repository serves as a comprehensive collection of examples and projects exploring various facets of Generative AI, with a strong emphasis on Large Language Models (LLMs), their diverse integrations, and advanced AI techniques such as Retrieval-Augmented Generation (RAG) systems and autonomous AI agents.

## Key Technologies/Frameworks
- **Core Language:** Python
- **LLM Orchestration:** LangChain, LangChain-Core
- **LLM Providers:** OpenAI, Anthropic, Google Generative AI (Gemini), Hugging Face Transformers
- **Vector Stores:** FAISS
- **Document Processing:** PyPDFLoader, RecursiveCharacterTextSplitter
- **Tools:** DuckDuckGo Search, python-dotenv
- **Data Science:** NumPy, scikit-learn

## Main Features
- Implementation and integration of various LLMs (OpenAI, Gemini, Anthropic, Hugging Face).
- Development of AI agents utilizing the ReAct (Reason and Act) pattern for dynamic task execution.
- Construction of end-to-end Retrieval-Augmented Generation (RAG) systems for informed Q&A from custom documents.
- Exploration of fundamental components: document loaders, text splitters, embedding models, vector stores, and retrievers.
- Demonstrations of prompt engineering, chat model interactions, and structured output parsing.

## Architectural Patterns
- **ReAct Agents:** Employs a iterative reasoning and action loop where LLMs interact with external tools (e.g., search) to achieve goals.
- **Retrieval-Augmented Generation (RAG):** Integrates information retrieval from a knowledge base (e.g., PDF documents in a FAISS vector store) with LLM generation to produce accurate and context-aware responses.
- **Modular Design:** The codebase is organized into thematic modules, facilitating understanding, reuse, and independent development of various Generative AI components.