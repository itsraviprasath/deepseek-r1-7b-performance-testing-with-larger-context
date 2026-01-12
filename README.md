# Local LLM Large Context Benchmark (Ollama)

This repository documents hands-on experiments evaluating how a local
LLM (DeepSeek-R1:7B via Ollama) behaves when provided with increasingly
large context inputs such as coding standards, infra runbooks, and
schema documents.

The goal is to understand:
- How much context a local model can reliably handle
- When and how instruction-following degrades
- What failure modes appear with large documents

This is a practical, observation-based benchmark — not a synthetic one.
