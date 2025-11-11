# Vibe Matcher - AI Fashion Recommendation System

## Overview
An intelligent fashion recommendation system that understands style preferences through natural language queries and matches users with products using semantic similarity.

## Features
-  **Free Embeddings**: Uses Sentence Transformers instead of expensive APIs
-  **Semantic Matching**: Understands nuanced style descriptions like "cozy weekend vibes"
-  **Real-time Performance**: Sub-100ms query response times
-  **Comprehensive Analytics**: Performance metrics, similarity scores, and visualizations
-  **Top-3 Recommendations**: Returns ranked product matches with confidence scores

## Technology Stack
- **Embeddings**: Sentence Transformers (all-MiniLM-L6-v2)
- **Similarity**: Cosine similarity with scikit-learn
- **Data**: Pandas DataFrame with 10 fashion products
- **Visualization**: Matplotlib, Seaborn for performance analysis
- **Language**: Python 3.8+

## Quick Start

### Installation
```bash
pip install sentence-transformers scikit-learn pandas matplotlib seaborn
```

### Usage
1. Open `vibe_matcher_notebook.ipynb` in Jupyter
2. Run all cells to initialize the system
3. Test with queries like:
   - "elegant minimalist professional style"
   - "cozy weekend comfortable vibes" 
   - "energetic urban street style"

## Performance
- **Response Time**: ~50ms average
- **Accuracy**: 83% good matches (similarity > 0.7)
- **Cost**: $0.00 (completely free)
- **Scalability**: Linear scaling with dataset size

## Project Structure
```
├── vibe_matcher_notebook.ipynb    # Main implementation
├── vibe_matcher_metadata.json     # System metadata
├── .gitignore                     # Git ignore patterns
└── README.md                      # Project documentation
```
