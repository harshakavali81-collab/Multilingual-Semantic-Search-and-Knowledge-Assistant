# Model card: Multilingual Semantic Search and Knowledge Assistant

**Type:** search. **Data:** Six original parallel-language toy passages. **Split:** 18 synthetic near-text queries; no held-out corpus.

## Local results
- TF-IDF char n-grams: Recall@3 1.0000

## Limitations and safety
This is character TF-IDF over six toy passages, not neural embeddings or an LLM. A near-identical query benchmark is unusually easy.

The data and metrics do **not** provide external production validation. Reproduce a licensed real-dataset benchmark and independent error/fairness/safety analysis before real-world application.
