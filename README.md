# Language Detection and Translation

This project detects the language of a given text and translates it into a target language. It uses a Naive Bayes classifier for language detection and Hugging Face transformer models for translation.

## Features

- Detects language from text using `MultinomialNB`
- Translates text into a specified language using pretrained models
- Works with multiple languages present in your dataset
- Easy to extend for new languages

## Installation

Make sure you have Python 3.8+ installed. Install the required libraries:

```bash
pip install pandas numpy scikit-learn transformers torch sentencepiece

