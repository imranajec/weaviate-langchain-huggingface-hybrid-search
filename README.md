# Hybrid Search with Reranker using Weaviate, LangChain, Hugging Face, and Cohere

This repository implements a hybrid search system with a reranker using Weaviate, LangChain, Hugging Face, and Cohere. The project demonstrates how to combine keyword and vector searches to achieve efficient and relevant search results, enhanced by a reranking mechanism.
## Table of Contents 
- [Introduction](https://chatgpt.com/c/5f9d2d50-5630-46f0-95e1-8fb3bc4f450b#introduction) 
- [Features](https://chatgpt.com/c/5f9d2d50-5630-46f0-95e1-8fb3bc4f450b#features) 
- [Requirements](https://chatgpt.com/c/5f9d2d50-5630-46f0-95e1-8fb3bc4f450b#requirements) 
- [Usage]() 
- [Contributing]() 
- [License](https://chatgpt.com/c/5f9d2d50-5630-46f0-95e1-8fb3bc4f450b#license)

## Introduction

This project combines multiple tools to create a powerful hybrid search system. It leverages: 
- **Weaviate**  for storing and querying documents using hybrid search. 
- **LangChain**  for integrating retrieval mechanisms. 
- **Hugging Face**  for pre-trained language models. 
- **Cohere**  for reranking search results to improve relevance.
## Features
- Hybrid search combining keyword and vector searches.
- Efficient storage and retrieval of documents using Weaviate.
- Fine-tuned language models for enhanced search capabilities.
- Reranking of search results for improved relevance.
## Requirements
- Python 3.8 or higher
- Weaviate
- LangChain
- Hugging Face Transformers
- Cohere API
## Installation 
1. Clone the repository:

```bash
git clone https://github.com/imranajec/weaviate-langchain-huggingface-hybrid-search.git
cd weaviate-langchain-huggingface-hybrid-search
``` 

## Usage 
1. **Set up Weaviate** :
- Configure your Weaviate instance and ensure it is running. 
2. **Run the Jupyter Notebook** : 
- Open the `Hybrid_Search_with_CohereReranker.ipynb` file and follow the instructions to load documents, configure the search, and perform queries. 
3. **Run a Search Query** :
- Execute a search query and observe the hybrid search results with reranked outputs.

## License

This project is licensed under the MIT License.

---

