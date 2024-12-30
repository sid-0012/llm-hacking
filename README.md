# llm-hacking

# Universal Adversarial Attacks on the Facebook RAG Retriever

## Overview
This repository accompanies the paper *Universal Adversarial Attacks on the Facebook RAG Retriever* by Sean O’Brien, Chengsong Diao, and Sidney Pan from UC San Diego. The research demonstrates the feasibility of creating universal adversarial prefixes that manipulate Facebook RAG (Retrieval-Augmented Generation) retrievers to favor malicious or irrelevant documents. These findings reveal potential vulnerabilities in RAG systems that could lead to misinformation, hallucinations, or compromised LLM safety.

## Key Contributions
- **Adversarial Prefix Optimization:** Developed methods to generate 32-token prefixes that maximize document similarity scores across a variety of queries, outperforming relevant documents retrieved by RAG systems.
- **Generalization:** Demonstrated that prefixes trained on Wikipedia data generalize effectively to unseen datasets and instruction styles.
- **Robustness Analysis:** Evaluated attack effectiveness on both in-domain and out-of-domain payloads, highlighting the versatility and threat posed by adversarial prefixes.
- **Visualization and Impact:** Explored embedding visualization to illustrate the systematic shift caused by adversarial prefixes in the retriever's embedding space.




