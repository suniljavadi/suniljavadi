# Deployment Status

Verified on 2026-09-16.

## Live Applications

| Project | Platform | URL | Verified behavior |
| --- | --- | --- | --- |
| RAG Q&A System | Streamlit Community Cloud | https://rag-app-system-shxft5zzpqhv5jpxvmdhe3.streamlit.app/ | UI loads and builds an in-memory FAISS index from `example.txt`; OpenAI questions require the app secret |
| Enterprise Text-to-SQL AI Agent | Streamlit Community Cloud | https://suniljavadi.streamlit.app/ | Deterministic synthetic demo query returns SQL, validation, and rows |
| OpenAI Streamlit Chatbot | Streamlit Community Cloud | https://app-openai-chatbot-edkp7lvx2nwjnz4gatqk5u.streamlit.app/ | UI loads; OpenAI secret must be configured before chat use |
| Portfolio | GitHub Pages | https://suniljavadi.github.io/sunil-portfolio/ | Static portfolio loads |

## Deployment Ready, Access Required

These applications have meaningful web/API deployment value and local Docker/test support, but no public backend URL has been verified:

- `AI-Log-Analyzer-RCA-Agent`
- `Enterprise-RAG-Meeting-Intelligence-Agent`
- `Meeting-Notes-Professional-Email`
- `AI-Agent-Jira-Integration`
- `AI-SQL-Optimizer`
- `ai-document-intelligence-editor`
- `Multi-Agent-AI-Data-Engineering-Assistant`

The remaining blocker is authenticated access to a backend hosting provider and, where required, a managed PostgreSQL service. No paid infrastructure was created.

## Not Applicable For Public Deployment

- `Machine-Learning` and `Deep-Learning` notebook collections
- `SQL` and `Power-BI` learning collections
- Azure sample/reference repositories
- `streamlit-practice-apps` learning collection
- `text-to-sql-api` prototype, superseded by the deployed Text-to-SQL application
- `suniljavadi-profile` documentation repository

These remain source and learning artifacts rather than standalone public services.
