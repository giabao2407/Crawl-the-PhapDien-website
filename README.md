# Crawl-the-PhapDien-website
This project builds a vector database using ChromaDB and performs semantic search on Vietnamese legal documents. The dataset consists of full_ItemID.html files, which are processed and stored in ChromaDB using the bkai-foundation-models/vietnamese-bi-encoder embedding model.

Features

Data Ingestion: Extracts content from full_ItemID.html files and stores them in ChromaDB.

Metadata Storage: Saves the file path in metadata for easy retrieval.

Semantic Search: Finds the most relevant documents using vector similarity search.

Pre-trained Embedding Model: Uses bkai-foundation-models/vietnamese-bi-encoder for high-quality Vietnamese text embeddings.
### File Structure
.
├── BoPhapDienDienTu/
│   ├── vbpl/  # Contains full_ItemID.html files
├── chroma_db/  # Vector database storage
├── ingest_data.py  # Script to ingest documents into ChromaDB
├── search.py  # Script to perform semantic search
├── requirements.txt  # Dependencies
└── README.md  # Project documentation
