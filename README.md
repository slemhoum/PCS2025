# PCS2025-C13163_python-calc-scientifique2025
# Clustering Enron Emails for Process Mining – Mini Project

## 📂 Repository Structure

PCS2025_<Matricule>_python-calc-scientifique2025/
│
├── notebooks/
│ └── TP1_clustering_emails.ipynb # Jupyter notebook(s) for TPs and the mini-project
│
├── src/
│ └── clustering_from_scratch.py # Source code implementing K-Means clustering from scratch
│
├── data/
│ └── sample_emails.csv # Example or sample email data (or add download instructions)
│
├── report/
│ └── mini_project_report.pdf # The detailed report (objectives, methods, results, perspectives)
│
├── articles/
│ └── related_article.pdf # A recent research article related to BP extraction from emails
│
├── requirements.txt # List of required Python packages
├── README.md # This file


---

## 📝 Project Overview

This mini-project explores how **unsupervised clustering** can reveal process-related groupings in an enterprise email dataset (Enron).  
The primary focus is on using a **from-scratch implementation of K-Means clustering** to automatically categorize emails, paving the way for future work in business process mining from unstructured communication.

---

## 🎯 Objectives

- Clean and preprocess Enron email data.
- Engineer features from multiple email fields (subject, body, sender, recipient).
- Implement the K-Means clustering algorithm manually (no scikit-learn KMeans).
- Analyze and visualize clustering results.
- Discuss the implications for business process mining.

---

## 🛠️ Libraries Used

- **pandas**: Data loading, manipulation, and cleaning
- **numpy**: Numeric operations and K-Means implementation
- **scikit-learn**: TF-IDF feature extraction and PCA for visualization
- **matplotlib**: Data visualization

> See `requirements.txt` for installation.

---

## 📊 Data Description

- **Source:** [Enron Email Dataset (Kaggle)](https://www.kaggle.com/datasets/wcukierski/enron-email-dataset)
- **Data used:** A CSV extract of email communications.
- **Preprocessing:**  
    - Removed empty or very short email bodies  
    - Cleaned out special characters, email addresses, and URLs  
    - Combined subject, body, sender, and recipient for a richer feature set  
    - Transformed text to TF-IDF vectors (max 1500 features)

---

## ⚙️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/PCS2025/<Matricule>_python-calc-scientifique2025.git
   cd PCS2025_<Matricule>_python-calc-scientifique2025
