CyberShield URL Classifier 
🚀 Malicious vs Benign URL Detection using K-Means Clustering
📌 Overview

This project focuses on detecting malicious and benign URLs using unsupervised learning (K-Means Clustering). The dataset contains thousands of URLs labeled as good or bad. The main goal is to group URLs based on their similarity and observe patterns that help in identifying phishing or malicious sites.

📂 Dataset

Source: Combination of multiple malicious & benign URL datasets.

Size: ~549,000+ URLs

Columns:

URL → The website link

Label → Class (good / bad)

⚙️ Steps in Project

Data Loading & Cleaning

Combined multiple datasets into one.

Removed duplicates & null values.

Feature Extraction

Extracted URL length, number of dots (.), number of special characters, domain length, etc.

Clustering with K-Means

Applied K-Means Clustering to group URLs into clusters.

Evaluated clusters against actual labels.

Visualization

Plotted scatter plots & cluster separation.

Compared benign vs malicious distribution.

📊 Results

K-Means successfully grouped URLs into clusters.

Malicious URLs tend to have longer length, more subdomains, and suspicious patterns.

🔮 Future Scope

Apply supervised learning models (Logistic Regression, Random Forest, XGBoost).

Build a real-time malicious URL detector.

Deploy the model using Flask / FastAPI.

💻 Tech Stack

Python 🐍

Pandas, NumPy

Scikit-Learn

Matplotlib / Seaborn

📜 License

This project is licensed under the MIT License – free to use and modify.

⚡Maintainer: Syed Bilal Faiz
📧 bilalfaiz614@gmail.com

🔗 LinkedInhttps://www.linkedin.com/in/syed-bilal-faiz-262324247?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app 

