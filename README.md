# Q&A RAG Chatbot With Pinecone and NVIDIA Endpoints

A RAG chatbot for question-answering about Youtube courses. To do this, It is implemented the three following steps.

- step1: Engineered an ingester to embed and ingest documents into Pinecone using parallel batching
- step2: Designed a Semantic Search Engine for Youtube courses to embed and retrieve similar documents
with their sources, the title and url of courses
- step3: Connected all together using a Multi-hope Question-Answering RAG Chain 
