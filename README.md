# Stacked

Stacked is a side project that I am working on. It's an app that recommends books. It is hosted at [].

I followed the development of viberary, which is a project by @vboykis in 2023, and recently read her blog post [retro on viberary](https://vickiboykis.com/2024/01/05/retro-on-viberary/), that inspired me to build something similar. The project has to be something you're interested in, and I have been fortunate enough to work on real-world recommender systems. This project will teach me a lot about search and recsys and production systems in general.

In this project, I will build a transformer-based machine learning system.

## Tech Stack
1. Data in gzipped JSON files
2. DuckDB to process these JSON files
3. SBERT for encoding the documents into embeddings
5. Redis
6. FastAPI
7. ONNX
8. Streamlit UI
9. Dockerfile
10. Makefile
11. nginx
12. pre-commit
13. Locust
14. Loguru
15. Pytest

## Tooling
1. Paperspace
2. Digital Ocean droplets
3. Load balancer
4. Github Actions

## Architecture

I use the two-tower architecture that encodes user search queries and corpus using sentence transformers.
