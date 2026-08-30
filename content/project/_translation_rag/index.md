---
title: Translation RAG Service
summary: A lightweight Retrieval-Augmented Generation (RAG) backend for translation prompts. The service exposes a FastAPI REST API that stores translation pairs in SQLite — kept idempotent through database-level deduplication — retrieves the most relevant examples with TF-IDF cosine similarity, and assembles them into retrieval-augmented prompts for LLM-based translation. An additional heuristic component detects stammering in translated sentences, and the whole system ships Dockerized for easy deployment.
tags:
  - LLM
date: 2025-12-20
url_code: https://github.com/r4stin/translation-rag-service
---

A lightweight Retrieval-Augmented Generation (RAG) backend for translation prompts. The service exposes a FastAPI REST API that stores translation pairs in SQLite — kept idempotent through database-level deduplication — retrieves the most relevant examples with TF-IDF cosine similarity, and assembles them into retrieval-augmented prompts for LLM-based translation. An additional heuristic component detects stammering in translated sentences, and the whole system ships Dockerized for easy deployment.
