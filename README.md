# DOCUMENT CLASSIFICATION - LATENT SEMANTIC ANALYSIS (LSA)

## Overview
This project involves the classification of documents using Latent Semantic Analysis (LSA) in Python. LSA is a technique in natural language processing that helps in extracting and representing the contextual-usage meaning of words by statistical computations applied to a large corpus of text. The main goal of this project is to demonstrate how LSA can be used to classify documents based on their content.
The "Document Classification - Latent Semantic Analysis" project is an implementation of a machine learning technique for classifying textual documents based on their content. Latent Semantic Analysis (LSA) is employed to uncover the underlying structure in the relationships between terms and documents. By reducing the dimensionality of the Document-Term Matrix through Singular Value Decomposition (SVD), LSA captures the latent semantic relationships among terms, enabling more effective document classification.
Objectives
Text Preprocessing: Convert raw text data into a structured format suitable for analysis by removing noise, tokenizing text, and normalizing terms.
Document-Term Matrix (DTM) Creation: Represent the corpus as a matrix where rows correspond to documents and columns correspond to terms.
Latent Semantic Analysis (LSA): Apply SVD to the DTM to reduce dimensionality and extract meaningful latent concepts.
Document Classification: Use the reduced semantic space to measure document similarity and classify new documents based on their content.
Methodology
Text Preprocessing:

Tokenization: Split text into individual words or tokens.
Stop Words Removal: Eliminate common words that do not contribute to the meaning (e.g., "and," "the").
Stemming/Lemmatization: Reduce words to their root form to unify different grammatical forms of the same word.
DTM Creation: Construct a matrix representing the frequency of terms in each document.
Latent Semantic Analysis:

SVD Application: Decompose the DTM into three matrices (U, Sigma, VT) to capture the latent structure. U represents the document concept space, Sigma contains singular values representing the importance of each concept, and VT represents the term concept space.
Dimensionality Reduction: Select a reduced number of dimensions to retain significant concepts while discarding noise.
Document Classification:

Similarity Measurement: Compute cosine similarity between document vectors in the reduced semantic space.
Classification: Assign documents to categories based on their similarity to training documents.
## Features
- Document-Term Matrix creation
- Singular Value Decomposition (SVD)
- Document similarity measurement
- Document classification
- Tfidf Vectorizer
- svd truncation
- Topic Modelling 

## Requirements
- Python 3.x
- Required libraries:
  - scikit-learn
  

## Installation
1. **Clone the repository**
    ```bash
    git clone https://github.com/anaumsharif/DOCUMENT-CLASSIFICATION-LSA-.git
    cd document-classification-lsa
    ```



## Contributing
1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push to the branch.
5. Create a pull request.

## License
This project is licensed under the MIT License.

---

Feel free to reach out if you have any questions or need further assistance. Enjoy classifying documents with LSA!
