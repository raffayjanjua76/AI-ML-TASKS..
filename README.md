# AI-ML-TASKS..
This repository features my AI/ML Internship work at DevelopersHub Corporation. Key tasks include:  BERT Classifier: Fine-tuned DistilBERT for AG News classification with a live Gradio UI.  ML Pipeline: Built a production-ready Scikit-Learn churn prediction system with Joblib.  LLM Tagging: Used Zero-Shot learning for auto-tagging tickets.
# AI/ML Engineering Internship - DevelopersHub Corporation 🚀

This repository contains my solutions for the Advanced Task Set of the AI/ML Engineering Internship. These projects demonstrate my proficiency in Transformer models, production-grade ML pipelines, and Large Language Model (LLM) applications.

## 📂 Project Overview

### 1. News Topic Classifier Using BERT (Task 1)
*   **Objective:** Fine-tune a Transformer model to classify news headlines into four categories: World, Sports, Business, and Sci/Tech.
*   **Methodology:** Utilized `distilbert-base-uncased` for a balance of speed and performance. Fine-tuned using the Hugging Face `Trainer` API on the AG News dataset.
*   **Deployment:** Integrated a live web UI using **Gradio** for real-time headline classification.

### 2. End-to-End ML Pipeline for Churn Prediction (Task 2)
*   **Objective:** Build a reusable, production-ready pipeline to predict customer churn using the Telco dataset.
*   **Methodology:** Developed a robust **Scikit-Learn Pipeline** that automates missing value imputation, feature scaling, and categorical encoding.
*   **Optimization:** Employed `GridSearchCV` for hyperparameter tuning of a Random Forest model and exported the final artifact using `joblib` for seamless deployment.

### 3. Auto Tagging Support Tickets via Zero-Shot LLM (Task 5)
*   **Objective:** Automate the categorization of unstructured support tickets using Large Language Models.
*   **Methodology:** Implemented **Zero-Shot Classification** using the `facebook/bart-large-mnli` model.
*   **Highlight:** The system performs semantic analysis to rank the Top 3 most probable tags per ticket without requiring any labeled training data.

---

## 🛠️ Tech Stack
*   **NLP:** Hugging Face Transformers (BERT/BART), Tokenizers.
*   **Machine Learning:** Scikit-Learn, Pandas, NumPy, Joblib.
*   **Deployment:** Gradio, Streamlit.
*   **Development:** Python, Google Colab, PyTorch.

## 📈 Key Results
*   Successfully achieved high F1-scores on news classification.
*   Created a "leak-proof" ML pipeline that handles raw data to prediction in one call.
*   Developed a scalable LLM-based triage system for customer support automation.

## 👨‍💻 Submission Details
*   **Internship:** AI/ML Engineering at DevelopersHub Corporation.
*   **Deadline:** 25 May, 2026.
*   **Submission:** GitHub Repository & Google Classroom.
