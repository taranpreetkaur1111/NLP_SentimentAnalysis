# NLP Sentiment Analysis: Traditional Machine Learning vs Deep Learning

A comprehensive Natural Language Processing (NLP) project that compares traditional machine learning and deep learning approaches for sentiment classification on customer reviews. This project evaluates multiple models, including classical ML algorithms, a BiLSTM network, and a fine-tuned DistilBERT transformer, while analyzing model interpretability and performance.

---

## Project Overview

The objective of this project is to classify customer reviews into sentiment categories and compare the effectiveness of traditional machine learning techniques with modern deep learning and transformer-based models.

The project includes:

- End-to-end text preprocessing
- Traditional machine learning models
- Deep learning using BiLSTM
- Transformer fine-tuning using DistilBERT
- Hyperparameter tuning
- Model evaluation and comparison
- Explainable AI using LIME
- Performance analysis across multiple evaluation metrics

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- PyTorch
- Hugging Face Transformers
- DistilBERT
- BiLSTM
- LIME
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Preprocessing

- Data cleaning
- Missing value handling
- Text normalization
- Tokenization
- Stop-word removal
- Train / Validation / Test split

---

### 2. Traditional Machine Learning

Implemented baseline NLP models using feature engineering techniques.

Examples include:

- TF-IDF Vectorization
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

### 3. Deep Learning

Implemented a Bidirectional LSTM (BiLSTM) model for sentiment classification.

Features include:

- Word embeddings
- Sequence padding
- Hyperparameter tuning
- Validation monitoring
- Performance comparison against classical ML models

---

### 4. Transformer Fine-Tuning

Fine-tuned a pretrained DistilBERT model using Hugging Face Transformers.

Key tasks included:

- Tokenization using DistilBERT tokenizer
- Transfer learning
- Fine-tuning on sentiment dataset
- Evaluation on unseen test data

---

### 5. Explainable AI

Used LIME to interpret model predictions by identifying words that contributed most to sentiment classification.

Also analyzed:

- Attention visualization
- Important features
- Model confidence

---

## Model Evaluation

The models were compared using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix

Additional analysis included:

- Performance by review length
- Vocabulary distribution
- Error analysis

---

## Results

This project demonstrates the progression from traditional NLP pipelines to transformer-based architectures.

Key findings include:

- Transformer models significantly improved sentiment classification performance.
- BiLSTM outperformed several traditional machine learning models.
- Explainability techniques provided insights into model decision-making.
- Fine-tuning pretrained language models reduced manual feature engineering while improving accuracy.

---

## Repository Structure

```
├── Final.ipynb
├── README.md
├── requirements.txt
├── data/
├── models/
├── outputs/
└── figures/
```

---

## Future Improvements

- Experiment with larger transformer models (RoBERTa, DeBERTa)
- Hyperparameter optimization using Optuna
- Deploy the model using FastAPI
- Containerize with Docker
- Build an inference API
- Add experiment tracking using MLflow

---

## Skills Demonstrated

- Natural Language Processing (NLP)
- Deep Learning
- Transformer Models
- Hugging Face Transformers
- PyTorch
- Scikit-learn
- Explainable AI (LIME)
- Model Evaluation
- Hyperparameter Tuning
- Data Preprocessing
- Python
