# Sentiment-Analysis-and-Modeling-for-Amazon

This project builds a Sentiment Analysis & Modeling Pipeline for Amazon Product Reviews, designed for end-to-end reproducibility and real-world deployment.

It processes raw customer reviews, transforms text into numerical features, trains machine learning models, and serves predictions through a production-ready API. The goal is to classify reviews as Positive or Negative based on the review text and star rating metadata.

# 🔑 Key Highlights

Data Pipeline: Cleans and normalizes raw Amazon reviews, creates binary sentiment labels (positive if rating ≥ 4, else negative).

Feature Engineering: Implements TF-IDF vectorization with configurable vocabulary size and n-gram ranges.

Modeling: Trains a Logistic Regression baseline, easily extendable to advanced models (e.g., transformers).

Evaluation: Provides accuracy, precision, recall, F1, ROC-AUC, and confusion matrix reports.

# Inference:

CLI tool for quick predictions on text input

FastAPI service with /predict endpoint for scalable deployment

Deployment Ready: Dockerfile for containerized API, CI/CD with GitHub Actions, and optional DVC for experiment tracking.

# 📂 Applications

Voice-of-Customer analytics

Product feedback monitoring

Market research & consumer behavior insights

Automating triage of customer reviews

# 🚀 Why This Project?

Amazon reviews are massive in scale and diverse in language style. Building a sentiment classifier on such data provides:

Hands-on exposure to real-world NLP challenges (noise, sarcasm, imbalanced data).

A reusable and extendable pipeline for other text classification tasks.

An industry-ready foundation for AI-powered customer experience tools.
