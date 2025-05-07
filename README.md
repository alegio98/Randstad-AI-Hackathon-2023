# 🏆 Randstad-AI-Hackathon-2023 - Winning project

This repository contains the winning solution of the Randstad AI Hackathon 2023, where participants were challenged to apply AI to real-world HR and recruitment problems. Our team developed an advanced NLP-based classification system that achieved top performance during the event.

🎯 Problem Statement
The goal was to build an AI model capable of classifying job offers written in Italian into predefined job categories. This task involved natural language understanding, domain-specific modeling, and high-accuracy classification.

🧠 Solution Overview
We fine-tuned a BERT-based transformer model (dbmdz/bert-base-italian-cased) using PyTorch and the HuggingFace Transformers library. The model was trained on labeled data consisting of job offer texts and their corresponding roles (e.g., Java Developer, Web Developer, etc.).

Key elements of our solution:

- Preprocessing and tokenization of text using AutoTokenizer
- Classification using AutoModelForSequenceClassification with 5 job classes
- Fine-tuning with custom training and evaluation loops
- Model selection based on the best F1-score on validation data
- Final model achieved F1 score ≈ 0.818, along with strong precision and recall

🛠️ Tech Stack
- Python 3
- PyTorch
- HuggingFace Transformers
- Scikit-learn
- Google Colab
- Pandas, NumPy

🥇 Outcome
Our solution was awarded first place among all participants for its effectiveness, innovation, and scalability.
