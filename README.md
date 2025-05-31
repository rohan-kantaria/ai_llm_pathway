# AI / LLM Upskilling & Portfolio (Monorepo)

This repository is the central home for my 4-month AI/LLM learning plan. It is structured as a “monorepo” where each folder under the root represents one day or one mini-project.

## Structure

- `Pipfile` / `Pipfile.lock` – Shared Pipenv environment (Python 3.13) for all subprojects.  
- `.gitignore` – Ignores virtualenvs, caches, logs, and other artifacts.  
- `day1-tokenizer/` – Day 1: Tokenizer demo (Hugging Face “gpt2” vs. “distilbert-base-uncased”).  
  - `src/tokenizer_demo.py` – Production-grade script.  
  - `tests/test_tokenizer_demo.py` – Pytest unit tests (adds `src/` to `PYTHONPATH`).  
  - `README.md` – Day 1-specific instructions.  
- `day2-prompting/` – Day 2: Prompt engineering experiments (future work).  
- `day3-rag/` – Day 3: RAG pipeline with FAISS (future work).  
- … and so on for each day.