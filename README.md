# TP d’IA agentique — LangChain et Groq

Notebook pédagogique , étudiant en deuxième année de Master AIDC. Il présente des exemples d’agents LangChain : mémoire, outils, sorties structurées, RAG et garde-fous.

## Préparation

Prérequis : Python 3.12 ou supérieur et [uv](https://docs.astral.sh/uv/).

```powershell
uv sync
uv add ipykernel langchain langchain-groq langgraph langgraph-checkpoint-sqlite python-dotenv ddgs langchain-experimental langchain-community langchain-huggingface sentence-transformers faiss-cpu langchain-tavily
Copy-Item .env.example .env
```

Renseignez vos clés `GROQ_API_KEY` et `TAVILY_API_KEY` dans `.env`. Ne publiez jamais ce fichier ni vos clés API.

Ouvrez `AI_Agentic_Groq.ipynb` dans VS Code, sélectionnez l’environnement `.venv` comme kernel Python, puis exécutez les cellules. Les cellules qui utilisent Groq, Tavily ou téléchargent un modèle nécessitent une connexion Internet et les clés correspondantes.
