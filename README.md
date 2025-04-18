# wikipedia-search-engine


**Wikipedia-Based Search Engine - Python Text Retrieval Project**  
This repository contains a Python-based information retrieval system that creates a local document corpus from random Wikipedia pages and allows users to search through it using a TF-IDF ranking model. It demonstrates basic text mining, preprocessing, and relevance scoring techniques.

---

📁 Repository Contents  
`Project2.ipynb`: Main notebook that creates the document corpus, builds the inverted index, computes TF-IDF scores, and implements a command-line search interface  

---

🌟 Project Features  
- Uses the `wikipedia` Python API to generate a local document collection  
- Preprocesses documents with tokenization, lowercasing, and stopword filtering  
- Builds an inverted index with term frequencies and document lengths  
- Implements TF-IDF scoring to rank documents for a given query  
- Includes a snippet extractor to preview query matches  
- Simple command-line interface for entering and viewing results  
- Fully written in Python with no external ML dependencies  

---

🚀 Usage Instructions  
To run this project locally:

### 1. Clone the repository

```bash
git clone https://github.com/mmassey1084/wikipedia-search-engine.git
cd tfidf_wiki_search
