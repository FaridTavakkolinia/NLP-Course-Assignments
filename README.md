# NLP Course Assignments - Verona University

This repository contains assignments completed as part of the Natural Language Processing (NLP) course at Verona University.

## Assignment 1 - Text Classification using Wikipedia

### Description
The objective of this assignment was to classify texts into two categories: geographic and non-geographic. The implementation used Python and NLTK, with the option to preprocess the text using stop word removal, stemming, and lemmatization. The assignment involved training classifiers using Naive Bayes and Logistic Regression approaches.

### Files
- `NLP_Assignments.ipynb`: Contains the implementation of the text classification algorithm, including data preprocessing, feature extraction, and model training.

### Solution Overview
1. **Text Retrieval**: Used Wikipedia API to retrieve content for given topics.
2. **Preprocessing**: Applied tokenization, stop word removal, stemming, and lemmatization.
3. **Feature Extraction**: Extracted features using Bag of Words and TF-IDF vectorization.
4. **Model Training**: Trained Naive Bayes and Logistic Regression classifiers.
5. **Classification**: Classified new texts into geographic and non-geographic categories.

## Assignment 2 - Text Summarization

### Description
The objective of this assignment was to implement an algorithm to generate summaries of input texts, following the style of another text. The implementation was done in Python using NLTK. The algorithm handles large documents by summarizing them hierarchically to fit within a context window limit.

### Files
- `NLP_Assignments.ipynb`: Contains the implementation of the hierarchical summarization algorithm.

### Solution Overview
1. **Measure Length**: Measured the length of the input documents.
2. **Proportional Length Calculation**: Computed target lengths proportionally based on the original document lengths.
3. **Document Slicing**: Sliced the documents into chunks that fit within the context window limit.
4. **Summarization**: Summarized each chunk and collated the summaries.
5. **Hierarchical Summarization**: Repeated summarization until the final summary fit within the context window limit.
6. **Saving Summaries**: Saved the summarized documents to files.

## Note
These assignments are part of the NLP course at Verona University, demonstrating fundamental techniques in text classification and summarization using Python and NLTK.
