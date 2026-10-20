# Hi, I'm Shashank Chikattimala

Senior Software Engineer at Lowe's in Charlotte, NC, with 15 years of shipping enterprise software. I'm applying that engineering discipline to production AI: retrieval, agents, and the evaluation that tells you whether they actually work.

## What I care about

Building small systems and **measuring them honestly**: labelled test sets, confidence intervals, and writing down what did not work.

## Projects

- **[kube-rag](https://github.com/shashankcm/kube-rag)**: an agentic RAG service over Kubernetes docs, evaluated with a quote-verified golden set and no LLM judge. Measured that a cross-encoder reranker adds +0.077 hit@5 and +0.106 MRR (95% CIs exclude zero), and that the planner's query rewrite cost 0.09 MRR until I fixed it. Includes CI and 92 tests.
- **[production-rag-1](https://github.com/shashankcm/production-rag-1)**: a hardened LLM API (rate limiting, injection and PII checks, cache, model fallback, output validation). Its 56 tests found a crash in the retry graph, error text returned as an answer, and 500 responses that leaked internals.
- **[langc-project](https://github.com/shashankcm/langc-project)**: runnable demos of semantic chunking, hybrid BM25 + dense search with reciprocal rank fusion, cost controls and tracing.

## Find me

[Portfolio](https://portfolio.shashankuidev9.workers.dev) · [LinkedIn](https://www.linkedin.com/in/shashankcm90) · [Email](mailto:shashankuidev9@gmail.com)
