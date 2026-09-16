# Deployment Status

Verified on 2026-09-16.

## Live Applications

| Project | Platform | URL | Verified behavior |
| --- | --- | --- | --- |
| RAG Q&A System | Streamlit Community Cloud | https://rag-app-system-shxft5zzpqhv5jpxvmdhe3.streamlit.app/ | Historical browser verification recorded UI loading, in-memory FAISS construction, and a grounded document response; OpenAI questions require the app secret |
| Enterprise Text-to-SQL AI Agent | Streamlit Community Cloud | https://suniljavadi.streamlit.app/ | Historical deterministic smoke evidence recorded SQL, rows, execution time, and read-only validation; the latest checkpoint confirmed hosted deterministic demo mode, while an unsafe-query case remains pending |
| OpenAI Streamlit Chatbot | Streamlit Community Cloud | https://app-openai-chatbot-edkp7lvx2nwjnz4gatqk5u.streamlit.app/ | Historical browser smoke test returned `Hello!`; the latest checkpoint rendered the UI but had a disabled Send control and no new response |
| Meeting Notes Professional Email API | Render free tier | https://meeting-notes-professional-email.onrender.com/health | `/health`, `/docs`, and `/openapi.json` returned 200; valid and invalid API requests were verified; free-tier wake behavior remains unverified |
| Portfolio | GitHub Pages | https://suniljavadi.github.io/sunil-portfolio/ | Static portfolio loads |

## Deployment Ready, Access Required

These applications have meaningful web/API deployment value and local Docker/test support, but no public backend URL has been verified:

- `AI-Log-Analyzer-RCA-Agent`
- `Enterprise-RAG-Meeting-Intelligence-Agent`
- `Meeting-Notes-Professional-Email` Streamlit UI is not separately hosted; its API is live above
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

## Evidence Note

HTTP reachability, rendered UI, completed browser interaction, local tests, and semantic evaluation are separate evidence levels. A historical smoke test remains valid evidence for its recorded session, but it is not presented as a fresh interaction result when the current browser state cannot reproduce it.
