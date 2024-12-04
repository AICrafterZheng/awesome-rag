# Awesome RAG (Retrieval Augmented Generation) 🚀

A curated list of advanced RAG techniques and implementations to enhance your LLM applications.

## Table of Contents
- [Basic RAG](#basic-rag)
- [BM25/Sparse RAG](#bm25sparse-rag)
- [ReRanker RAG](#reranker-rag)
- [Hybrid RAG](#hybrid-rag)
- [Sentence Window RAG](#sentence-window-rag)
- [Auto Merging RAG](#auto-merging-rag)
- [HyDE RAG](#hyde-rag)
- [Query Transformation RAG](#query-transformation-rag)
- [Self Query RAG](#self-query-rag)
- [RAG Fusion](#rag-fusion)
- [RAPTOR](#raptor)
- [ColBERT RAG](#colbert-rag)
- [Graph RAG](#graph-rag)
- [Agnostic RAG](#agnostic-rag)
- [Vision RAG](#vision-rag)

## Basic RAG
Basic RAG (Retrieval Augmented Generation) is the foundational approach where documents are embedded, stored, and retrieved based on similarity to enhance LLM responses with relevant context.

## BM25/Sparse RAG
BM25 (Best Match 25) is a sparse retrieval technique that uses term frequency and document length to rank documents, providing an efficient alternative to dense retrievers.

## ReRanker RAG
ReRanker RAG implements a two-stage retrieval process where an initial set of documents is retrieved and then re-ranked using a more sophisticated model to improve relevance.

## Hybrid RAG
Hybrid RAG combines multiple retrieval methods (e.g., dense and sparse) to leverage the strengths of each approach, typically achieving better results than single-method retrieval.

## Sentence Window RAG
Sentence Window RAG retrieves relevant text passages and includes surrounding context (sentences before and after) to provide more complete information to the LLM.

## Auto Merging RAG
Auto Merging RAG automatically combines multiple retrieved chunks into coherent context windows, optimizing the input for the LLM while maintaining relevance.

## HyDE RAG
Hypothetical Document Embeddings (HyDE) generates synthetic documents based on the query before retrieval, helping to bridge the semantic gap between queries and documents.

## Query Transformation RAG
Query Transformation RAG enhances retrieval by reformulating the original query into multiple variations, capturing different aspects and improving recall.

## Self Query RAG
Self Query RAG enables the LLM to decompose complex queries into structured components, allowing for more precise and filtered retrieval operations.

## RAG Fusion
RAG Fusion combines results from multiple retrieval rounds or strategies, using techniques like Reciprocal Rank Fusion to create more robust and accurate results.

## RAPTOR
RAPTOR (Retrieval Augmented Processing through Task-Oriented Representations) optimizes retrieval by generating task-specific embeddings and retrieval strategies.

## ColBERT RAG
ColBERT RAG utilizes late interaction between query and document terms, enabling more fine-grained matching while maintaining efficiency.

## Graph RAG
Graph RAG leverages graph structures and relationships between documents to enhance retrieval and provide more contextually relevant information.

## Agnostic RAG
Agnostic RAG implements retrieval systems that can work with multiple embedding models and retrieval strategies, providing flexibility and adaptability.

## Vision RAG
Vision RAG extends retrieval capabilities to include image understanding and multimodal context, enabling more comprehensive information retrieval and generation.

## Contributing
Feel free to submit a PR to add more RAG techniques or improve existing descriptions!