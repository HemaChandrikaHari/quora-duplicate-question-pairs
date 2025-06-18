Quora Question Pairs - Semantic Similarity Detection
This project focuses on detecting whether two given questions are semantically equivalent. The dataset used is from the Quora Question Pairs Kaggle competition. The aim is to build an NLP model that can identify duplicate questions based on their semantic meaning rather than just surface-level text similarity.

📌 Problem Statement

Many users on Quora tend to ask questions that are semantically similar but phrased differently. The objective of this project is to predict whether a pair of questions are duplicates or not.

For example:

“How do I learn machine learning?”

“What is the best way to start learning ML?”

Though phrased differently, these two questions mean the same thing. Accurately identifying such pairs helps improve search quality, reduce redundancy, and enhance user experience on Q&A platforms.

📂 Dataset
Source: [Quora Question Pairs | Kaggle](https://www.kaggle.com/c/quora-question-pairs
)

Dataset Contents:

id – ID of the pair of questions

qid1, qid2 – Unique IDs of each question

question1, question2 – The actual text of the two questions

is_duplicate – Target label (1 if duplicate, 0 otherwise)

