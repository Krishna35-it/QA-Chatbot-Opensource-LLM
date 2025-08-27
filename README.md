# QA-Chatbot-Opensource-LLM (Streamlit + LangChain + Ollama)
A simple Q&amp;A chatbot built with Streamlit and LangChain that runs on a local Ollama model.

**Default model:** `gemma3:1b` (selectable in the sidebar).

## Features
1) Clean Streamlit UI with a text input and instant answer display
2) Model picker in the sidebar (default: `gemma3:1b`)
3) Adjustable temperature and max tokens sliders
4) Minimal LangChain pipeline (Prompt → LLM → Text output)

## Tech Stack
1) **Frontend:** Streamlit
2) **LLM Orchestration:** LangChain
3) **Model Runtime:** Ollama (local)
4) **Optional Tracing:** LangSmith (via `LANGCHAIN_API_KEY`)

## Prerequisites
- Python 3.10+ recommended
- [Ollama](https://ollama.com/) installed and running
- Pull the model locally (first time only):
  ```bash
  ollama pull gemma3:1b
