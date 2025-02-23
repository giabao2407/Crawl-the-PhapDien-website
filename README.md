# Crawl-the-PhapDien-website
Builds a vector database using ChromaDB and performs semantic search on Vietnamese legal documents. The dataset consists of full_ItemID.html files, which are processed and stored in ChromaDB using embedding model.

Features

Data Ingestion: Extracts content from full_ItemID.html files and stores them in ChromaDB.

Metadata Storage: Saves the file path in metadata for easy retrieval.

Semantic Search: Finds the most relevant documents using vector similarity search.

Pre-trained Embedding Model: Uses bkai-foundation-models/vietnamese-bi-encoder for high-quality Vietnamese text embeddings.


