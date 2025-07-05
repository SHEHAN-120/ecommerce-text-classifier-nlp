# Product Category Classifier Using NLP and Decision Tree

This project is a Natural Language Processing (NLP) based multi-class text classification system. It classifies e-commerce product descriptions into one of four predefined categories: `households`, `electronics`, `clothing`, or `books`.

The model uses **TF-IDF vectorization** to convert text data into numerical features, and a **Decision Tree Classifier** to perform multi-class classification.

---

## 🧠 Project Objective

To create an intelligent model that can predict the appropriate category label for a product based solely on its textual description.

---

## 🧰 Tools & Technologies

- Python (Google Colab)
- `pandas`, `numpy`
- `scikit-learn`
  - `TfidfVectorizer` for feature extraction
  - `DecisionTreeClassifier` for classification
  - `train_test_split` for data partitioning
  - `classification_report` for evaluation

---

## 🔍 NLP Techniques Used

- **Text Vectorization:** Used `TfidfVectorizer` to transform product descriptions into TF-IDF feature vectors.
- **Multi-class Classification:** Applied `DecisionTreeClassifier` to classify into 4 product categories.
- **Model Evaluation:** Used precision, recall, F1-score, and accuracy to evaluate performance.

---

## 🧪 Workflow Summary

1. Load and inspect the dataset
2. Preprocess the text data
3. Vectorize text using `TfidfVectorizer`
4. Train a Decision Tree classifier
5. Evaluate the model performance

---
