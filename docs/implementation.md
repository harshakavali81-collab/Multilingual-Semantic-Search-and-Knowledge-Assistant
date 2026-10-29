# Implementation and evaluation — Multilingual Semantic Search and Knowledge Assistant

End-to-end local workflow: deterministic synthetic or bundled sample input → input validation → task-appropriate split (18 synthetic near-text queries; no held-out corpus) → baseline/model comparison → metrics → serialized model → FastAPI route → error handling and unit tests.

Run `python engine.py train` and `python -m unittest discover -s tests -v`; launch `uvicorn api:app --reload` and inspect `/docs`.

**Scope limitations:** This is character TF-IDF over six toy passages, not neural embeddings or an LLM. A near-identical query benchmark is unusually easy. No production monitoring, public web hosting or verified external integrations are claimed.
