---
title: "LLM Interpretability and Evaluation"
date: 2026-01-13
summary: "Studied Transformer internal logic and implemented RAG to address the 'black-box' nature of LLMs"
weight: 2
---

## Context
Understanding why LLMs hallucinate requires moving beyond the prompt level. The focus was to break down the Transformer architecture，specifically how attention heads weigh information and test if providing a grounded context through RAG could override a model's internal "guessing."

## What I did
- Architecture Breakdown: Dissected the Transformer block, specifically the roles of Query (Q), Key (K), and Value (V) in calculating self-attention scores through dot-product and Softmax normalization
- RAG Workflow: Set up a retrieval system using ChromaDB to index technical papers, forcing the model to prioritize retrieved chunks over its pre-trained weights
- Internal Analysis: Explored how Tokenization and Embedding layers transform raw text into high-dimensional vectors, and how Positional Encoding preserves sequence order without recurrent structures

## Takeaways
The core of LLM reliability lies in how the Attention mechanism weights different tokens. By implementing RAG, I saw that we can effectively "re-weight" the model's focus toward factual data. It's not just about the prompt; it's about how the Context Window is utilized to steer the Softmax probability away from hallucinated token
