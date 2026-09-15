# Sunil Javadi

### AI / GenAI Engineer with a Data Engineering Foundation

I build practical AI systems with Python, SQL, RAG, FastAPI, Streamlit, and controlled tool workflows. My focus is the engineering around the model: trustworthy data, validation, evaluation, observability, and safe deployment.

[Portfolio](https://suniljavadi.github.io/sunil-portfolio/) · [LinkedIn](https://www.linkedin.com/in/sunil-javadi/) · [Resume](https://github.com/suniljavadi/sunil-portfolio/blob/main/Javadisunil_AI_Engineer_Resume.pdf) · [Email](mailto:javadisunil@gmail.com)

## Live Demos

| Project | Status | Link | Source |
| --- | --- | --- | --- |
| OpenAI Chatbot | Browser smoke test passed | [Open app](https://app-openai-chatbot-edkp7lvx2nwjnz4gatqk5u.streamlit.app/) | [Repository](https://github.com/suniljavadi/streamlit-openai-chatbot) |
| RAG Q&A System | Public page reachable | [Open app](https://rag-app-system-shxft5zzpqhv5jpxvmdhe3.streamlit.app/) | [Repository](https://github.com/suniljavadi/rag-qa-system) |
| Text-to-SQL Agent | Public page reachable; local evaluator corrected and validated | [Open app](https://suniljavadi.streamlit.app/) | [Repository](https://github.com/suniljavadi/Text-to-SQL-AI-Agent) |
| Meeting Notes API | Health endpoint reachable; 11 tests passed | [Health check](https://meeting-notes-professional-email.onrender.com/health) | [Repository](https://github.com/suniljavadi/Meeting-Notes-Professional-Email) |

Public reachability means the page or endpoint responded. It does not, by itself, claim production readiness or complete semantic accuracy.

## Featured Projects

### Safe Text-to-SQL

Natural-language analytics over synthetic business data. The system retrieves schema and KPI context, generates candidate SQL, validates it, and executes only bounded read queries.

**Evidence:** 10 tests passed; corrected local evaluation reports 90% execution accuracy and 80% semantic correctness on the repository’s synthetic evaluator.

### Grounded RAG

Document retrieval, embeddings, context construction, and answer generation with an explicit insufficient-evidence path.

**Focus:** retrieval quality, freshness, citations, authorization filters, and groundedness rather than fluent text alone.

### Meeting Notes Workflow

Structured extraction of summaries, decisions, actions, risks, and open questions followed by a reviewable professional email draft.

**Evidence:** 11 tests passed; outbound communication remains an approval-gated production concern.

### AI Log Analyzer and RCA

Operational log parsing, normalization, historical incident retrieval, diagnostic evidence, hypotheses, severity, and confidence.

**Evidence:** 11 tests passed locally; the project is deployable but intentionally not presented as publicly hosted.

## Engineering Themes

- Ground model output in documents, schemas, metrics, or source notes.
- Treat generated SQL, tools, and external actions as untrusted until validated.
- Keep sensitive actions read-only or approval-gated.
- Separate health checks, smoke tests, local tests, and quality evaluation.
- Measure correctness, groundedness, safety, latency, cost, and failure behavior.
- Use synthetic data for public demonstrations and protect secrets through environment configuration.

## Technical Stack

**Python · SQL · FastAPI · Streamlit · PostgreSQL · SQLite · SQLAlchemy · Pydantic · sqlglot · LangChain · FAISS · OpenAI-compatible APIs · Docker · pytest · GitHub Actions**

## Data-to-AI Progression

```text
SQL / ETL / BI → Data Engineering → Python → ML → LLM Apps / RAG →
Safe Agents / Tool Calling → Evaluation and Production AI
```

## What I Am Building Toward

AI systems that are useful in real workflows and defensible in production discussions: explicit data contracts, safe execution boundaries, repeatable evaluation, observable deployments, and clear human ownership.

## More

- [Portfolio website](https://suniljavadi.github.io/sunil-portfolio/)
- [AI Log Analyzer](https://github.com/suniljavadi/AI-Log-Analyzer-RCA-Agent)
- [Enterprise RAG Knowledge Assistant](https://github.com/suniljavadi/Enterprise-RAG-Confluence-Knowledge-Assistant)
- [Machine Learning](https://github.com/suniljavadi/Machine-Learning)
- [Deep Learning](https://github.com/suniljavadi/Deep-Learning)
- [SQL Practice](https://github.com/suniljavadi/SQL)
- [Power BI Portfolio](https://github.com/suniljavadi/Power-BI)
