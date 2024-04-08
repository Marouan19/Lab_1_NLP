# Lab 1: Arabic NLP Pipeline

## Introduction
This Jupyter Notebook contains code for an Arabic Natural Language Processing (NLP) pipeline developed during Lab 1. The pipeline performs various NLP tasks on Arabic news articles scraped from the BBC Arabic website. The purpose of this Atelier is to demonstrate the application of various NLP techniques to process Arabic text data and extract useful information from it.

## Overview
In this Lab, we focused on building an end-to-end NLP pipeline for processing Arabic text. The pipeline includes the following steps:
1. **Data Collection**: Scraping Arabic news articles from the BBC Arabic website.
2. **Text Cleaning**: Removing HTML tags, URLs, email IDs, and non-Arabic characters from the text data.
3. **Spelling Correction**: Using TextBlob library to correct spelling mistakes in the text.
4. **Stopword Removal**: Utilizing NLTK library to remove stopwords from the text.
5. **Stemming and Lemmatization**: Performing stemming and lemmatization on the text to normalize word forms.
6. **Part-of-Speech Tagging**: Extracting Part-of-Speech (POS) tags using the Stanza library.
7. **Named Entity Recognition (NER)**: Extracting Named Entities using NER with Stanza.

## Synthesis
Through this Lab, I gained hands-on experience in implementing various NLP techniques for Arabic text processing. Some key takeaways include:
- Understanding the importance of data preprocessing steps such as cleaning, spelling correction, and stopword removal in NLP tasks.
- Learning about different linguistic features of Arabic text and how to analyze them using POS tagging and NER.
- Gaining proficiency in using popular NLP libraries such as NLTK and Stanza for Arabic text processing.
- Acquiring skills to build an end-to-end NLP pipeline capable of extracting valuable insights from Arabic text data.

## Usage
To use the pipeline:
1. Clone or download this Jupyter Notebook to your local machine.
2. Ensure you have Jupyter Notebook installed along with the required libraries specified in the notebook (e.g., requests, BeautifulSoup, pymongo, stanza, nltk, TextBlob).
3. Run each cell in the notebook sequentially to execute the entire NLP pipeline on the Arabic news articles.

# Contributors
- Developed by Marouan DAGHMOUMI
- Supervised by Lotfi AACHAK
