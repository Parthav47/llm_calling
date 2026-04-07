# AI Foundation

This repository tracks my **6-week intensive study plan** to become internship-ready as an AI engineer.  
Each folder contains working code from that day's learning — not tutorials, but actual builds.  

Covered topics include:
- Prompt engineering
- Structured outputs
- RAG pipelines
- LangChain
- LangGraph
- Agentic systems

---

## Progress Tracker

### Week 1: LLM Fundamentals & Prompt Engineering ✅
**Goal:** Understand LLM internals, master prompt engineering, and build a production-ready summarizer.

---

### Core Files
- **`llm_calling.ipynb`**: Initial exploration of API protocols, tokenization, and context windows.  
- **`CLI_Groq_Web_summarizer.ipynb`**: A terminal-style tool using Groq (Llama-3.3-70b) for high-speed web scraping and extraction.

---

### Key Skills Mastered
Week 1
- **Transformer Intuition**: Tokens, attention mechanisms, and next-token prediction.  
- **Prompt Engineering**: Iterating through Zero-shot, Few-shot, and Chain-of-Thought (CoT) prompting.  
- **Structured Outputs**: Enforcing strict JSON schemas for reliable data extraction.  
- **Production Robustness**: Implementing backoff timers for rate limits and `try-except` blocks for scraping failures.


###  What I Learned (Week 1)
- **Tokens & Context Windows**: LLMs process tokens, not words; managing context windows is critical for cost and performance.  
- **Temperature & Sampling**: Experimented with values from `0.0` to `1.0` to balance deterministic logic vs. creative variety.  
- **JSON Mode is Non-Negotiable**: For production AI, free-text responses are risky. Learned to enforce `response_format={"type": "json_object"}` for parseable outputs.  
- **Scraping Cleanliness**: Removing boilerplate tags (`nav`, `footer`, etc.) significantly improves summary quality.  
- **CLI Portability**: Built a self-bootstrapping script that installs dependencies automatically, making it runnable in any standard Linux/Windows terminal.

---
