# 📧 Spam Mail Detection Project

## 📌 Overview

This repository contains three distinct implementations of a **Spam Mail Detection System**, showcasing different levels of complexity and technology. The implementations include:  
1. 🏷️ **Simple Machine Learning Approach**  
2. 🎭 **Spam Detection with NLTK & Bernoulli Naive Bayes** deployed using **Streamlit**  
3. 🚀 **Advanced Classification using BERT** for state-of-the-art performance  

Each implementation is in a separate folder with its own `README.md` file containing detailed information.

---

## 📂 Project Structure

```plaintext
📂 spam-mail-detection/
│
├── 📂 simple-way/
│   └── 📄 README.md  # Simple Machine Learning implementation
│
├── 📂 streamlit-nltk/
│   └── 📄 README.md  # Naive Bayes implementation with Streamlit deployment
│
├── 📂 bert-implementation/
│   └── 📄 README.md  # BERT-based advanced classification
│
└── 📄 README.md      # This file
```

---

## 🔍 Implementation Details

### 1️⃣ Simple Machine Learning Approach
- **📁 Folder**: `simple-way/`
- **🛠️ Key Features**:
  - Utilizes **CountVectorizer** for text vectorization.
  - Handles class imbalance with **SMOTE**.
  - Models used: Logistic Regression and Random Forest.
- **📊 Performance**:
  - High accuracy (~99%) and balanced precision/recall for both spam and ham messages.
- **✅ Best For**: Quick implementation with minimal resource usage.

---

### 2️⃣ Spam Detection with Naive Bayes and Streamlit
- **📁 Folder**: `streamlit-nltk/`
- **🛠️ Key Features**:
  - Preprocessing with **NLTK** (tokenization, stopword removal, stemming).
  - **TF-IDF** vectorization for feature extraction.
  - Deploys a **Streamlit Web App** for interactive predictions.
- **📊 Performance**:
  - **Bernoulli Naive Bayes** achieved ~99% accuracy.
- **✅ Best For**: Interactive and user-friendly web application.

---

### 3️⃣ Advanced Email Classification using BERT
- **📁 Folder**: `bert-implementation/`
- **🛠️ Key Features**:
  - Implements **BERT** for robust feature extraction and classification.
  - Fine-tuned on a spam email dataset.
  - Designed for execution in **Google Colab** with GPU acceleration.
- **📊 Performance**:
  - Achieved ~99% accuracy with excellent recall and precision.
- **✅ Best For**: Advanced applications requiring high accuracy and state-of-the-art NLP.

---

## 🚀 How to Use This Repository

### 🛠️ Prerequisites
1. 🐍 Python 3.8+ installed.
2. 📦 Necessary libraries installed (`pip install -r requirements.txt` for each implementation).

### 🔄 Steps:
1. Navigate to the desired folder (`simple-way/`, `streamlit-nltk/`, or `bert-implementation/`).
2. Follow the instructions in the respective `README.md` file to run the implementation.

---

## 📊 Comparison of Approaches

| ⚡ Approach                 | 🔬 Technique              | 🌍 Deployment  | 🎯 Accuracy | 📌 Best Use Case                            |
|----------------------------|---------------------------|---------------|------------|---------------------------------------------|
| **Simple ML Approach**      | CountVectorizer + SMOTE  | Notebook      | 99%        | Basic implementation with minimal setup.    |
| **Streamlit + Naive Bayes** | TF-IDF + Bernoulli NB    | Streamlit Web | 99%        | User-friendly, interactive web application. |
| **BERT Implementation**     | Transformer (BERT)       | Google Colab  | 99%        | Advanced use cases with state-of-the-art NLP. |

---

## 👥 Contributors

- **Bipin Waghmare**  
  - 🔗 [LinkedIn](https://www.linkedin.com/in/bipin-waghmare-2bb623167/)  
  - 🐙 [GitHub](https://github.com/bipinwaghmare)

---

## 📜 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🙌 Acknowledgments

Special thanks to:
- 🧠 **Scikit-learn**, **NLTK**, and **Transformers** teams for providing essential libraries.
- 🌐 **Streamlit** for simplifying web app deployment.
- 📊 The open-source community for datasets and resources.

