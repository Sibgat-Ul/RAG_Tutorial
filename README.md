## Rag applications in different approaches

This repository contains the implementation of the RAG model in different approaches. The RAG model is a model that combines retrieval and generation in a single model. The model is composed of three components: retriever, reader, and generator. The retriever is responsible for retrieving relevant documents from a large corpus, the reader is responsible for reading the retrieved documents and extracting the relevant information, and the generator is responsible for generating the final answer. The RAG model is a powerful model that can be used in different applications such as question answering, text summarization, and text generation.

### Approaches
1. Basic rag application without any vector database
2. Rag application with Haystack (RAG_in_Haystack.ipynb)
3. Rag application with Huggingface + duck duck go search + Mistral-7b (local)/Gemini-2b(inference endpoint) (RAG_w_Huggingface.ipynb)
4. Rag application with Huggingface + weaviate (vector database) + tavily search api