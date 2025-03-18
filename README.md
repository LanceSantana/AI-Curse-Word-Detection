# Curse Word Detection and Replacement

This project focuses on detecting and replacing profane words in text data using various techniques, including **profanity censoring, K-Nearest Neighbors (KNN), and synonym replacement**. The dataset used for this project is sourced from Reddit comments.

## Features

- **Data Cleaning**: Removes non-English text, URLs, special characters, and duplicate comments.
- **Profanity Detection**: Uses the `better_profanity` library to identify profanity in text.
- **Exploratory Data Analysis (EDA)**: Analyzes profanity occurrence across different subreddits and generates a profanity word cloud.
- **Profanity Handling Techniques**:
  - **Technique 1: Profanity Censoring** – Replaces detected profanity with asterisks.
  - **Technique 2: KNN-based Replacement** – Finds similar non-profane sentences and replaces words.
  - **Technique 3: Synonym Replacement** – Uses WordNet and Word2Vec to replace profanity with appropriate synonyms.
