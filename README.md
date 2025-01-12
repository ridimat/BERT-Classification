# BERT-Classification
Project Overview
This project focuses on building a complaint classification model using BERT (Bidirectional Encoder Representations from Transformers). The goal is to classify customer complaints into predefined categories to improve ticket processing efficiency and generate insights.

The data for this project consists of customer complaints sourced from a JSON file, which has been preprocessed and used to fine-tune the BERT model for sequence classification.

Features
Preprocessing: Cleaned and lemmatized text data, removed noise, and extracted relevant features.
EDA (Exploratory Data Analysis):
Visualized complaint distributions by product and category.
Analyzed complaint text lengths and timely responses.
Identified top complaint issues by category.
Fine-Tuning BERT:
Tokenized text using the bert-base-uncased tokenizer.
Fine-tuned the pre-trained BERT model for classification into 5 predefined categories:
Credit card / Prepaid card
Bank account services
Theft/Dispute reporting
Mortgages/loans
Others
Evaluation: Measured the performance of the fine-tuned BERT model using accuracy and loss metrics.

Dataset:
The dataset contains customer complaints data in JSON format. Due to size constraints, the data is hosted on Google Drive. You can download the data from the link below:
https://drive.google.com/file/d/1PQz6iDH1WrJIyn-myhRfvdfgvN6qEvPq/view?usp=sharing

