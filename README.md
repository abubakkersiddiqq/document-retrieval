# Document Retrieval

This project is a complete **CSV-based document retrieval system** that uses semantic search to find the most relevant rows based on a natural-language query.  
It combines embeddings, vector search, fuzzy matching, and CSV processing into one clean pipeline.

---

## Features

- **CSV Loading:** Reads and processes large CSV files using `pandas`.  
- **Column Detection:** Uses fuzzy matching (`thefuzz`) to identify which column matches the user's query.  
- **Semantic Embeddings:** Generates vector embeddings using Sentence Transformers (`all-MiniLM-L6-v2`).  
- **Vector Database:** Stores and retrieves embeddings using ChromaDB.  
- **Full Retrieval Pipeline:**  
  _Query → Column Match → Embed → Vector Search → Result_

---

## Tech Stack

- Python  
- pandas  
- sentence-transformers  
- chromadb  
- thefuzz

---
### Example Output

![Search Result](./output1.png)

