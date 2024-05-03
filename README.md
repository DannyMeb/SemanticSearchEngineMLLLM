# Semantic Search Engine for Academic Articles

This repository contains the source code for a semantic search engine designed to enhance the retrieval of academic articles using advanced NLP and machine learning techniques. The project integrates a vector space model with Term Frequency-Inverse Document Frequency (TF-IDF) and cosine similarity for document ranking, alongside OpenAI's ChatGPT for dynamic query refinement.

## Project Structure

- `data/`: Directory where the collected data is stored.
- `data_collection.ipynb`: Jupyter notebook used for collecting data.
- `build_vector_model.ipynb`: Jupyter notebook for building the Information Retrieval (IR) system.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- Jupyter Notebook
- Required Python libraries: `numpy`, `pandas`, `scikit-learn`, `nltk`

You can install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn nltk
