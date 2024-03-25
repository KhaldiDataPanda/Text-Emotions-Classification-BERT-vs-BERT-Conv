# <p style="padding:10px; background-color:#4B7BE5; color:white; font-family:Georgia, serif; font-size:24px; text-align:center; border-radius:10px;">Table of Contents 📚</p>

<div style="border:2px solid #4B7BE5; background-color:#E8EFF5; padding:15px; border-radius:10px;">

* **[1. Project Goal 🎯](#1)**
    - Classifying emotions in text using a fine-tuned BERT model

* **[2. Dataset 📂](#2)**
    - Emotions dataset from Kaggle
    - Text and label columns with 6 emotion classes

* **[3. Importing Libraries 📥](#3)**
    - PyTorch, Transformers, and other useful libraries

* **[4. Data Analysis 📊](#4)**
    - Reading and analyzing the dataset
    - Plotting label value counts and addressing imbalance

* **[5. Data Preparation 🔧](#5)**
    - Creating a PyTorch custom class for dataset balancing
    - Train/test split, tokenization, and data loaders

* **[6. Modeling: Approach 1 ⚙️](#6)**
    - BERT model with pooling and fully connected layers
    - Using nn.parallel for GPU acceleration
    - Cross-entropy loss and training/testing loops

* **[7. Results: Approach 1 📈](#7)**
    - Achieved ~93% F1 score

* **[8. Modeling: Approach 2 ⚙️](#8)**
    - Adding convolutional layers with dropouts to the model

* **[9. Results: Approach 2 📈](#9)**
    - Upgraded to ~95% F1 score with excellent precision and recall

</div>
