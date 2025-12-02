# Document Retrieval

This project is a **CSV-based document retrieval foundation** that prepares the full pipeline for semantic search.  
It includes CSV loading, embedding setup, ChromaDB initialization, and a structure ready for retrieval logic.

---

## Features

- **CSV Loading:** Reads and processes large CSV files using `pandas`.  
- **Semantic Embeddings Setup:** Sentence Transformer model ready (`all-MiniLM-L6-v2`).  
- **Vector Database Ready:** ChromaDB client initialized for future storage and retrieval.  
- **Project Foundation:** Retrieval pipeline and fuzzy/rapidfuzz logic will be implemented after the exam.  

---

## Tech Stack

- Python  
- pandas  
- sentence-transformers  
- chromadb  
- rapidfuzz

---

## Example Output

### 🔹 Retrieval Result (Example)
![Search Result](./images/output-2.png)

### 🔹 CSV Preview (Snippet)
![CSV Preview](./images/sample-csv.png)
