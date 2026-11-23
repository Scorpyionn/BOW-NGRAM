# Experiment 4: Bag-of-Words (BoW) and N-Gram Models

## Overview
This experiment demonstrates the implementation of Bag-of-Words (BoW) and N-Gram models using Python and Scikit-learn.

A Food Delivery text dataset is used to analyze word frequencies and identify meaningful word combinations through Unigram, Bigram and Trigram models.

## Aim
To construct Bag-of-Words and N-Gram models from a corpus of documents and analyze the frequency distribution of words and phrases for text representation.

## Objectives
- Understand Bag-of-Words representation.
- Generate Unigram, Bigram and Trigram models.
- Analyze word frequency distributions.
- Convert text documents into numerical representations.
- Visualize frequently occurring words using a bar chart.

## Technologies Used
- Python 3
- Google Colab
- Scikit-learn
- Pandas
- Matplotlib

## Dataset
The experiment uses five sample sentences based on Food Delivery applications.

Example:
- I order pizza from the food delivery app.
- The delivery service provides fresh food.
- I like ordering burgers and pizza online.
- Food delivery apps offer fast service.
- Fresh burgers are available for online orders.

## Implementation Steps
1. Import the required libraries.
2. Create a text corpus containing five documents.
3. Generate the Bag-of-Words representation using CountVectorizer.
4. Generate Unigram features.
5. Generate Bigram features.
6. Generate Trigram features.
7. Calculate word frequency distributions.
8. Visualize the top 10 frequent words using a bar chart.

## Installation

Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn
```

## Repository Structure

```text
NLP_Practical_Experiments/
│
├── Experiment_4_BOW_NGRAM.ipynb
│
└── README.md
```

## Expected Output
The experiment generates:

- Bag-of-Words numerical representation.
- Unigram word features.
- Bigram phrase features.
- Trigram phrase features.
- Word frequency distribution.
- Top 10 word frequency bar chart.

## Applications
- Natural Language Processing
- Text Mining
- Sentiment Analysis
- Document Classification
- Information Retrieval
- Text Representation

## Result
Bag-of-Words and N-Gram models were successfully generated using a Food Delivery text corpus. Word frequency distributions were calculated and visualized to analyze frequently occurring words and phrases.

## Conclusion
Bag-of-Words and N-Gram techniques provide effective methods for representing textual data numerically. These techniques help identify word frequencies and meaningful word sequences, making them useful for Natural Language Processing and machine learning applications.

---

**Tools:** Python | Scikit-learn | Pandas | Matplotlib | Google Colab
