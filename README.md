# 🛡️ AI-Based Phishing Email Detector

An NLP-powered phishing email detection system using Large Language Models (LLMs) like **LLaMA** and **LangChain**. This project analyzes email tone, intent, and structure to flag suspicious content, achieving a **92% detection accuracy** in testing.

---

## 📌 Features

- ⚠️ **Phishing Detection**: Identifies urgent language, fake sender requests, and suspicious formatting.
- 🧠 **LLM-Based Analysis**: Uses LLaMA + LangChain to understand the semantic intent of email text.
- 📊 **High Accuracy**: Achieved **92% detection rate** on a curated dataset of phishing vs. legitimate emails.
- 🔍 **Explainability**: Highlights key phishing indicators in flagged emails (optional enhancement).

---

## 🧪 Tech Stack

- **Python**
- **LLaMA (Large Language Model)**
- **LangChain**
- **Scikit-learn / Pandas** *(for evaluation and preprocessing)*

---

## 🚀 How It Works

1. **Preprocess Emails**: Clean and normalize text input (removes signatures, headers, etc.).
2. **Intent Analysis**: Use LLaMA with LangChain to infer tone, urgency, and malicious intent.
3. **Phishing Flagging**: Based on semantic signals, the system classifies the email as *phishing* or *safe*.
4. **Evaluation**: Compares predicted labels with ground truth using standard NLP metrics.

---

## 📁 Project Structure

