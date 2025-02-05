# Sentiment Analysis with VADER Algorithm and RoBERTa Model

## Overview

This project implements sentiment analysis using two different approaches:

1. **VADER Algorithm**: A rule-based sentiment analysis tool particularly suited for social media and short text.
2. **RoBERTa Model**: A pre-trained transformer-based model fine-tuned for sentiment classification.

The repository demonstrates how to use these tools for analyzing the sentiment (positive, negative, or neutral) of text data and comparing their performance.

## Features

- Perform sentiment analysis using VADER and RoBERTa.
- Preprocess text data for analysis.
- Visualize sentiment distribution and compare results between the two methods.
- Easily extendable to other datasets and models.

## Installation

### Prerequisites

Ensure you have Python 3.8 or higher installed. You also need the following Python packages:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `transformers`
- `torch`
- `nltk`

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Fujelhrx/Sentiment-Analysis.git
   cd Sentiment-Analysis
   ```
2. Install the required packages:
   ```bash
   pip install -r requirement.txt
   ```


## Files

- `sentiment_analysis.py`: Script for sentiment analysis using VADER and RoBERTa Model.
- `requirements.txt`: List of required Python packages.
- `README.md`: Project documentation.

## Methodology

### VADER

VADER (Valence Aware Dictionary and sEntiment Reasoner) uses a lexicon and rule-based approach to analyze sentiment. It provides:

- Positive, Negative, Neutral scores.
- A Compound score (overall sentiment).

### RoBERTa

RoBERTa (A Robustly Optimized BERT Approach) is a transformer model fine-tuned for text classification tasks. It provides:

- Sentiment probabilities for each class (positive, negative, neutral).

## Example Results

Below is an example comparison of VADER and RoBERTa sentiment scores:

| Text                 | VADER Sentiment | RoBERTa Sentiment |
|----------------------|----------------|-------------------|
| "I love this movie!" | Positive        | Positive          |
| "This is terrible."  | Negative        | Negative          |
| "It's okay."         | Neutral         | Neutral           |

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed explanation.


## Acknowledgments

- [VADER Sentiment Analysis Tool](https://github.com/cjhutto/vaderSentiment)
- [Hugging Face Transformers](https://huggingface.co/transformers/)

## Contact

For any questions or feedback, please contact [Me](machhaliyafujel@gmail.com).
