# Word2Vec from Scratch

This repository contains a manual implementation of the **Word2Vec** model, built entirely from scratch without relying on any off-the-shelf, state-of-the-art libraries or models. The project is an educational exploration of how Word2Vec works under the hood, demonstrating the core concepts of word embeddings and their training mechanisms.

## Project Description
The goal of this project is to:
- Understand and implement Word2Vec using foundational Python libraries.
- Build a **Continuous Bag of Words (CBOW)** architecture with a window size of 3.
- Train word embeddings on a real-world corpus.

### Corpus
The dataset used for training is obtained from **Kaggle** and contains Reddit news headlines from a specific period. This corpus serves as the source for learning meaningful word representations.

### Current Status
- [WIP as of 05.01.2025]
  - Initial implementation of CBOW architecture is complete.
  - Focus is on preprocessing text and building the training pipeline.
  - Further optimizations and extensions, such as Skip-gram architecture, are planned.

## Key Features
- **Manual Implementation:** No external NLP libraries are used; everything is coded from scratch.
- **CBOW Training:** Implements the CBOW approach to predict target words based on context.
- **Corpus Preprocessing:** Includes text tokenization, vocabulary creation, and handling of noise in the dataset.