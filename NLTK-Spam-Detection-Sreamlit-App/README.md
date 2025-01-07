# Spam Detection Project

---

## Overview

This project focuses on detecting spam messages in emails and SMS using a machine learning approach. The implementation utilizes Bernoulli Naive Bayes as the primary classification model, achieving impressive results with high accuracy and precision.

---

## Highlights

- **Domain**: Natural Language Processing (NLP)
- **Objective**: Classify messages as "Spam" or "Not Spam"
- **Model**: Bernoulli Naive Bayes
- **Deployment**: Streamlit Web Application

---

## Dataset

- The dataset comprises labeled email/SMS messages.
- **Class Distribution**:
  - **Not Spam (0)**: 917 samples
  - **Spam (1)**: 117 samples

---

## Model Performance

### Evaluation Metrics

| Metric         | Class 0 (Not Spam) | Class 1 (Spam) |
|----------------|--------------------|----------------|
| Precision      | **0.99**           | **0.96**       |
| Recall         | **1.00**           | **0.94**       |
| F1-Score       | **0.99**           | **0.95**       |

**Overall Performance**:
- **Accuracy**: 99%
- **Macro Average**: Precision: **0.98**, Recall: **0.97**, F1-Score: **0.97**
- **Weighted Average**: Precision: **0.99**, Recall: **0.99**, F1-Score: **0.99**

---

## Key Features

1. **Preprocessing**: 
   - Tokenization, stopword removal, and stemming for text cleaning.
   - TF-IDF vectorization for feature extraction.

2. **Modeling**:
   - Bernoulli Naive Bayes for efficient binary classification.

3. **Deployment**:
   - Interactive Streamlit application for easy usability.

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your_username/spam-detection-app.git
cd spam-detection-app
```

### 2. Install Dependencies

Ensure you have Python 3.8+ installed. Run the following command:

```bash
pip install -r requirements.txt
```

### 3. Download NLTK Resources

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

### 4. Run the Streamlit App

```bash
streamlit run app.py
```

### 5. Usage

1. Open the app in your browser (default URL: `http://localhost:8501`).
2. Enter an email/SMS text in the input box.
3. Click the **Predict** button to see the result: **Spam** or **Not Spam**.

---

## Future Enhancements

- **Multi-Language Support**: Extend preprocessing for non-English messages.
- **Advanced Models**: Explore Random Forest, Gradient Boosting, or deep learning techniques.
- **Real-Time Updates**: Integrate with email servers for live spam filtering.
- **Mobile App**: Develop a mobile version for broader accessibility.

---

## Contributors

- **Bipin Waghmare**  
  - [LinkedIn](https://www.linkedin.com/in/bipin-waghmare-2bb623167/)  
  - [GitHub](https://github.com/bipinwaghmare)

Feel free to fork this repository and contribute!

---

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## Acknowledgments

Special thanks to:
- The NLTK and Scikit-learn teams for providing essential libraries for NLP and machine learning.
- Streamlit for simplifying web app deployment.

---
