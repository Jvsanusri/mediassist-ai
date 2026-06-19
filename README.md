# 🏥 MediAssist AI — Hospital Intelligence Platform

## What it does
AI system that helps hospitals with:
- 🚨 Patient Triage (classify Emergency/Urgent/Normal)
- 📚 Medical Knowledge Q&A (symptoms, drugs, protocols)
- 📅 Appointment Management (book + remember history)
- 🔐 Doctor Approval (HITL before any decision)
- 🛡️ Safety Guardrails (never diagnose, only inform)

## Tech Stack
| Layer | Technology |
|-------|-----------|
| LLM | Groq (Llama-3.3-70b) |
| Framework | LangChain + LangGraph |
| RAG | ChromaDB + BM25 Hybrid |
| API | FastAPI |
| Monitoring | LangSmith |
| Deploy | Docker + Kubernetes |

## Architectureclear