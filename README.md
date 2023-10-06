# NLP Pipeline for PMBOK 6th and PMI PRM Standards

A Natural Language Processing (NLP) pipeline for processing and analyzing unstructured text data from PMBOK 6th and PMI PRM standards.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## About

This project aims to provide a comprehensive NLP pipeline for processing text data from PMBOK 6th edition and PMI PRM standards. It performs various NLP tasks, including text cleaning, tokenization, part-of-speech tagging, stopwords removal, lemmatization, chunking, concept identification, relationship extraction, and frequency analysis. Additionally, it utilizes NLP models such as SBERT, KBERT, TOPICBERT, and the REBEL model for specific NLP tasks.

## Features

- Data Acquisition: Obtains unstructured text data from PMBOK 6th and PMI PRM standards.
- Text Cleaning: Cleans the data by removing irrelevant characters, symbols, and formatting issues.
- Tokenization and Normalization: Breaks the text into tokens and normalizes the text (e.g., lowercase).
- POS Tagging: Tags words with their part-of-speech information.
- Stopwords Removal: Eliminates common stopwords that do not contribute to the analysis.
- Lemmatization: Reduces words to their base forms.
- Chunking: Groups words into meaningful phrases or chunks.
- Concept Identification: Identifies concepts and their instances in the text.
- Relationship Extraction: Determines relationships between identified concepts.
- Frequency Analysis: Calculates the frequencies of concept appearances to identify relevant concepts.
- Utilize NLP Models: Utilizes models like SBERT, KBERT, TOPICBERT, and the REBEL model for specific NLP tasks.

## Data science requirements:

Data Retrieval : Gather and consolidate data from PMBOK 6th best practices and PMI's practice standard for Project Risk Management.
Data preprocessing: The data needs to be cleaned and preprocessed before it can be used to build the conceptual graph and train the recommender engine. This may involve tasks such as tokenization, normalization, stop word removal, and stemming.
Conceptual Graph Creation: Develop a structured conceptual graph representing key PRM concepts, relationships, and properties.
Model training: The recommender engine needs to be trained on an ontology of historical PRM issues and their resolutions. This can be done using a variety of machine learning techniques, such as collaborative filtering, content-based filtering, or hybrid approaches.
Performance Metrics: Define predictive performance metrics, such as recommendation accuracy and relevance, to continuously improve the predictive analytics component.

## Business requirements:

The system should be able to recommend PRM issues to project managers based on their specific needs and context. The recommendations should be personalized and relevant to the project manager's current tasks and priorities.
The system should be easy to use and understand. Project managers should be able to easily interact with the system to filter and sort recommendations, and to provide feedback on the system's performance.
The system should be scalable and able to handle a large volume of data. The system should be able to provide recommendations to project managers in real time, even as the dataset of PRM issues grows.


## Getting Started

### Prerequisites

Before running the NLP pipeline, ensure you have the following prerequisites:

- Python (>=3.6)
- Libraries: NLTK, spaCy, sentence-transformers

You can install the required Python libraries using pip:

```bash
pip install nltk spacy sentence-transformers
"# ProjetAI" 
