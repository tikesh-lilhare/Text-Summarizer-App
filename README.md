## 📝 Text Summarizer using Hugging Face Transformers

## 📌 Overview
This project is an AI-powered Text Summarization System that automatically generates concise and meaningful summaries from lengthy text documents using the T5 (Text-to-Text Transfer Transformer) model from Hugging Face Transformers. The model is fine-tuned on a text summarization dataset to produce high-quality abstractive summaries while preserving the original context.The application provides a simple and interactive interface through a FastAPI backend, allowing users to input long passages and receive summarized content in real time.

---

## 🛠️ Tech Stack
## Programming Language
Python
## Deep Learning & NLP
- Hugging Face Transformers
- T5 Transformer
- PyTorch
- Tokenizers
## Backend
- FastAPI
- Uvicorn
## Data Processing
- Pandas
- NumPy
- Scikit-learn
## Model Training
- Fine-Tuning
- Transfer Learning

---

## ⚙️ Project Workflow
<img width="1536" height="1024" alt="ChatGPT Image Jul 10, 2026, 01_31_25 PM" src="https://github.com/user-attachments/assets/2eca4e9e-d24b-44e3-b2fc-9bceceb4378b" />


---
## 🧠 Model Architecture

The project uses the T5 (Text-to-Text Transfer Transformer) model developed by Google and available through the Hugging Face Transformers library.

The workflow includes:
- Data preprocessing
- Tokenization
- Sequence encoding
- Transformer encoder-decoder architecture
- Fine-tuning on a summarization dataset
- Summary generation using beam search decoding

---

## 🔄 Model Training Pipeline
- Load Dataset
- Clean and preprocess text
- Tokenize using T5 Tokenizer
- Split dataset into training and validation sets
- Fine-tune the pretrained T5 model
- Evaluate model performance
- Save the trained model
- Deploy using FastAPI

---

## Project Screenshot

<img width="1896" height="878" alt="Screenshot 2026-07-10 133437" src="https://github.com/user-attachments/assets/2eccacc8-2f0c-4c3f-98d0-7e9c964896a8" />


---
