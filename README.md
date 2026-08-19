# SMS Spam Classification with NLP

## 📌 Project Overview

This project uses **Natural Language Processing (NLP)** and Machine Learning to classify SMS messages as either **Spam** or **Ham (legitimate)**.

The project processes text messages, converts them into numerical features using **TF-IDF**, and uses **Logistic Regression** to classify new messages.

The project was developed and tested using **Google Colab**.

## 🎯 Project Objectives

* Load and explore an SMS dataset
* Clean and preprocess text data
* Analyze message patterns
* Convert text into numerical features
* Train a Machine Learning classification model
* Predict whether messages are Spam or Ham
* Evaluate model performance
* Identify words associated with Spam and Ham messages

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TF-IDF
* Logistic Regression
* Google Colab

## 🧠 Natural Language Processing

The project applies several text preprocessing techniques:

* Lowercase conversion
* URL removal
* Special character removal
* Extra whitespace removal
* TF-IDF vectorization
* Unigram and bigram features

## 🤖 Machine Learning Model

The project uses **Logistic Regression** for binary text classification.

The target variable is:

* `0` → Ham
* `1` → Spam

## 🔄 NLP & Machine Learning Pipeline

```text
SMS Dataset
     ↓
Data Exploration
     ↓
Data Cleaning
     ↓
Text Preprocessing
     ↓
TF-IDF Vectorization
     ↓
Train / Test Split
     ↓
Logistic Regression
     ↓
Spam Prediction
     ↓
Model Evaluation
     ↓
Important Word Analysis
```

## 📊 Exploratory Data Analysis

The project analyzes:

* Spam vs Ham distribution
* Message length
* Differences between Spam and Ham messages
* Words that strongly influence classification

## 📈 Model Evaluation

The model is evaluated using:

* Accuracy
* ROC-AUC
* Precision
* Recall
* F1-score
* Confusion Matrix

The notebook automatically displays the evaluation results.

## 🔎 Custom SMS Prediction

The project also includes a function that allows new SMS messages to be tested.

Example:

```python
predict_sms("Congratulations! You have won a free prize!")
```

The model returns:

* Predicted class
* Spam probability

## 📂 Project Structure

```text
SMS-Spam-Classification-NLP/
│
├── SMS_Spam_Classification_NLP.ipynb
├── README.md
└── requirements.txt
```

## ▶️ How to Run the Project

1. Open `SMS_Spam_Classification_NLP.ipynb` in **Google Colab**.
2. Run the notebook from beginning to end.
3. The dataset is loaded automatically.
4. The SMS messages are cleaned and processed.
5. TF-IDF converts the text into numerical features.
6. The Logistic Regression model is trained.
7. The model predicts Spam and Ham messages.
8. Evaluation metrics and visualizations are generated.

## 🎓 Learning Outcomes

Through this project, I practiced:

* Natural Language Processing
* Text preprocessing
* TF-IDF vectorization
* Text classification
* Logistic Regression
* Model evaluation
* Confusion matrix analysis
* Feature interpretation
* Data visualization
* Machine Learning prediction

## 👩🏽‍💻 Author

**Sylviana VIGNIGBE**

B.Tech Computer Science & Engineering
Specialization: Artificial Intelligence & Machine Learning

## 📚 Project Purpose

This project was created as part of my learning journey in **Data Science, Machine Learning, Natural Language Processing, and Artificial Intelligence**.
