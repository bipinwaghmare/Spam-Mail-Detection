# Email Spam Detection - Machine Learning Approach

## Overview

This project implements an **Email Spam Detection System** using a straightforward machine learning pipeline. It focuses on handling class imbalance and efficient feature extraction to classify messages as `Spam` or `Ham` (Not Spam).

---

## Highlights

- **Text Vectorization**:
  - CountVectorizer to convert text data into numerical features.
- **Class Imbalance Handling**:
  - SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.
- **Machine Learning**:
  - Logistic Regression and Random Forest Classifiers applied for binary classification.
- **Evaluation**:
  - Metrics to assess model performance and identify areas of improvement.

---

## Dataset

- **Source**: Contains labeled email/SMS messages categorized as Spam or Ham.
- **Columns**:
  - `Label`: Spam or Ham.
  - `Message`: Content of the email/SMS.

### Dataset Summary:
- **Class Distribution**:
  - Spam: 885 samples
  - Ham: 859 samples

---

## Technologies Used

- **Python 3.8+**
- **Scikit-learn**: For CountVectorizer, SMOTE, and model building.
- **Pandas & NumPy**: For data manipulation.
- **Matplotlib & Seaborn**: For visualizations.

---

## Implementation Details

### 1. Data Preparation
- **Split Features and Labels**:
  - `X`: Text content of the messages.
  - `y`: Labels indicating Spam or Ham.

### 2. Feature Engineering
- **CountVectorizer**:
  - Converts text data into a matrix of token counts.
  - Provides numerical features for model input.

### 3. Class Imbalance Handling
- **SMOTE**:
  - Synthetic oversampling to balance the dataset by generating synthetic samples for the minority class (Spam).

### 4. Model Building
- **Train-Test Split**:
  - Data split into training (70%) and testing (30%) sets.
- **Models Applied**:
  - Logistic Regression
  - Random Forest Classifier

### 5. Model Evaluation
- **Logistic Regression Results**:
  - **Accuracy**: 99%
  - **Precision**: Spam: 0.98, Ham: 1.00
  - **Recall**: Spam: 1.00, Ham: 0.98
  - **F1-Score**: Spam: 0.99, Ham: 0.99
- **Random Forest Results**:
  - **Accuracy**: 99%
  - **Precision**: Spam: 0.98, Ham: 0.99
  - **Recall**: Spam: 0.99, Ham: 0.98
  - **F1-Score**: Spam: 0.99, Ham: 0.99
- **Visualization**:
  - Confusion matrix and classification report to analyze performance.

---

## Results

- **Performance Metrics**:
  - Logistic Regression and Random Forest both achieved high accuracy (99%) and balanced precision/recall for both classes.
  - SMOTE significantly improved the model's ability to correctly classify Spam messages.

---

## How to Run the Notebook

### Prerequisites
- Install Python 3.8+.
- Install required libraries:
  ```bash
  pip install -r requirements.txt
  ```

### Steps
1. Open the `email_spam.ipynb` file in Jupyter Notebook or Google Colab.
2. Execute the cells sequentially to:
   - Preprocess the dataset.
   - Train and test the models.
   - Evaluate performance metrics.

---

## Future Enhancements

- **Advanced Feature Extraction**:
  - Use TF-IDF or word embeddings for richer text representation.
- **Deep Learning Models**:
  - Explore neural networks like LSTMs or transformers for improved classification.
- **Real-Time Detection**:
  - Deploy the model for live email/SMS classification.

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

Special thanks to the Scikit-learn team for their contributions to the open-source community.
