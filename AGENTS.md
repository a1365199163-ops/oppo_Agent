# Project instructions

## Communication

- Communicate with the user in Chinese by default.
- Explain important decisions and risks in plain language.

## Long-term reference: OCT Agent

- Treat `G:\project\OCT_Agent-main` as a frequently used reference project for this repository.
- OCT Agent is a LangGraph-based multi-agent research assistant for optical coherence tomography (OCT).
- Its main capabilities are OCT strain estimation (vector, CNN, and Bayesian neural-network methods), a Deep Research workflow, and a Self-RAG local knowledge-base workflow.
- Its backend uses Python, LangGraph/LangChain, FastAPI, PyTorch, SciPy, and ChromaDB. Its frontend uses React, TypeScript, Vite, the LangGraph SDK, and Plotly.
- Its core interaction pattern is natural-language chat plus file attachments, with generated artifacts such as interactive heatmaps displayed in a result panel.

### How to use the reference

- Consult OCT Agent when work in this repository involves multi-agent orchestration, LangGraph graphs or subgraphs, research pipelines, RAG, file uploads, FastAPI services, React chat interfaces, or artifact/result panels.
- Read `G:\project\OCT_Agent-main\README.md` first, then inspect only the files relevant to the current task.
- Treat the reference project as read-only unless the user explicitly asks to modify it.
- Reuse architectural ideas and proven patterns when useful, but adapt them to this repository instead of copying code blindly.
- Keep this repository and OCT Agent independent; do not assume their dependencies, configuration, data, or deployment environments are interchangeable.
- Never open, copy, summarize, or expose `.env` files, API keys, tokens, credentials, or other secrets from the reference project.
- If the reference path is unavailable or has moved, tell the user before relying on assumptions about its current contents.
