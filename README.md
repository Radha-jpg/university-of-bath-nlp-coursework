# University of Bath - NLP Coursework

**Programme:** MSc Artificial Intelligence  
**Project:** IT Support Ticket Classification

## Overview
This project explores automated classification of IT support queries using Natural Language Processing (NLP) and Machine Learning.

Two preprocessing pipelines are compared using Logistic Regression across 308 queries and 14 IT support categories.

## Pipelines

- **Pipeline 1:** Snowball Stemming + Word TF-IDF.
- **Pipeline 2:** spaCy Lemmatisation + Hybrid Word and Character TF-IDF.

## Results

| Metric | Pipeline 1 | Pipeline 2 |
|---|---:|---:|
| Accuracy | 91.94% | 93.55% |
| Macro F1 | 0.9140 | 0.9341 |
| CV Macro F1 | 0.882 | 0.915 |

Pipeline 2 achieved better classification performance and more consistent cross-validation results.

## Technologies
- Python
- Pandas, NumPy
- NLTK, spaCy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Future Improvements
- Explore transformer-based models.
- Improve minority-class classification.
- Introduce active learning.

**Academic Project - University of Bath**
