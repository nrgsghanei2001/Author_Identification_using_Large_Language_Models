# Author Identification in Persian Literature using Language Models

## Project Overview

This project focuses on identifying authors in Persian literature using both traditional machine learning methods and modern language models like BERT. The work was divided into two main parts: dataset creation and author identification.

## Part 1: Dataset Creation

- **Objective:** Build a dataset of at least 10 Persian authors, each with 30 documents of exactly 500 words.
- **Approach:** 
  - Utilized web scraping techniques with Beautiful Soup in Python.
  - Ensured diversity in the dataset by selecting texts from the same literary genre.
  - Metadata such as author names and text content were included to maintain dataset integrity.
- **Challenges:** Addressed issues related to data collection and ensured the dataset was representative of the genre.

## Part 2: Author Identification

### Using BERT Models

- **Objective:** Fine-tune BERT models for the task of author identification.
- **Approach:** 
  - Selected and fine-tuned BERT models from Hugging Face tailored to this specific task.
  - Conducted experiments with 5-fold cross-validation to validate model performance.
- **Metrics:** Evaluated model performance using accuracy, F1 score, precision, recall, and confusion matrix.
- **Insights:** Explored the impact of fine-tuning parameters (e.g., learning rate), stopword omission, and document length on model performance.

### Using Traditional Machine Learning Methods

- **Objective:** Compare BERT models with traditional machine learning approaches.
- **Approach:** 
  - Implemented methods like Support Vector Machines (SVM), Random Forests, and Naive Bayes.
  - Preprocessed the text data, including tokenization, stopword removal, and TF-IDF vectorization.
- **Comparison:** 
  - Evaluated the performance of traditional ML models using the same metrics as for the BERT models.
  - Discussed the advantages and limitations of each approach.
