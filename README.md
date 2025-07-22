# Hate Speech Detector using BERT

A simple NLP classification model to detect hate speech in text using a pre-trained BERT model. This project was fine-tuned and deployed using Gradio.

## 🚀 Demo
[Insert Gradio link here if deployed]

## 🔧 Features
- BERT-based text classification (`bert-base-uncased`)
- Three class labels: `Hateful`, `Offensive`, `Neither`
- Gradio app for easy demo interface

## 🧠 How It Works
1. Input text is tokenized using HuggingFace tokenizer
2. Fed into a fine-tuned BERT model for classification
3. Output label is returned based on model prediction

## 🛠️ Stack Used
- Python
- PyTorch
- Transformers (HuggingFace)
- Gradio

## 📁 Files
- `app.py` – Gradio app script
- `model.pt` – Fine-tuned model (optional)
- `predict.py` – Prediction logic
- `README.md` – This file

## 🧪 Sample Inputs
- "Go back to your country" → Hateful
- "You're so dumb" → Offensive
- "Have a good day" → Neither

## ✅ Status
Project complete. Future work may include:
- Better training data
- Explainable AI integration
- Model accuracy evaluation

## 📌 Author
Hritik Kumar | [LinkedIn](https://linkedin.com/in/hritikkumar) | [Email](mailto:hritik01kumar@gmail.com)
