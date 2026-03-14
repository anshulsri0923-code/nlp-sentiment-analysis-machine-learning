

# 🚀 NLP Sentiment Analysis using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![NLP](https://img.shields.io/badge/NLP-TFIDF-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Description

This project implements a **Machine Learning based Sentiment Analysis system** using **Natural Language Processing (NLP)** techniques.

The model analyzes text data and automatically predicts the **sentiment of the text** such as:

* Positive 
* Negative 
* Neutral 

Sentiment analysis is widely used in:

* Social media monitoring
* Product review analysis
* Customer feedback analysis
* Opinion mining

This project demonstrates a **complete Machine Learning workflow from data preprocessing to model evaluation**.

---

# 🧠 Machine Learning Workflow

The following pipeline is used in this project:

```
Text Data
   │
   ▼
Text Preprocessing
   │
   ▼
Feature Extraction (TF-IDF)
   │
   ▼
Train-Test Split
   │
   ▼
Machine Learning Model
(Logistic Regression)
   │
   ▼
Model Evaluation
   │
   ▼
Sentiment Prediction
```

---

# 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **NLTK**
* **Scikit-learn**
* **Jupyter Notebook**

---

# 📂 Project Structure

```
sentiment-analysis-ml-project
│
├── sentiment_analysis_finalproject.ipynb
├── sentimentdataset.csv
├── model.pkl
├── vectorizer.pkl
└── README.md
```

---

# 📊 Dataset

The dataset contains **text samples labeled with sentiment categories**.

Example:

| Text                     | Sentiment |
| ------------------------ | --------- |
| I love this product      | Positive  |
| This service is terrible | Negative  |
| The product is okay      | Neutral   |

Columns used:

* **Text** → Input text
* **Sentiment** → Target variable

---

# 🔎 Exploratory Data Analysis (EDA)

EDA was performed to understand the dataset before training the model.

Key steps:

* Dataset inspection
* Checking missing values
* Sentiment distribution analysis
* Text length analysis

These steps help improve **data quality and model reliability**.

---

# 🧹 Text Preprocessing

Text preprocessing is essential in NLP.

Steps used in this project:

* Lowercasing text
* Removing punctuation
* Removing stopwords
* Tokenization
* Removing special characters

This helps **reduce noise and improve model performance**.

---

# 🔤 Feature Engineering

Since machine learning models require numerical input, text is converted into vectors using:

### TF-IDF Vectorization

TF-IDF measures the **importance of words in documents relative to the dataset**.

Benefits:

* Highlights important words
* Reduces impact of common words
* Improves classification accuracy

---

# 🤖 Machine Learning Model

The model used in this project:

### Logistic Regression

Reasons for choosing this model:

* Efficient for text classification
* Fast training time
* Works well with TF-IDF features
* Easy to interpret

Training steps:

1. Split dataset into training and testing sets
2. Train model using TF-IDF features
3. Evaluate model performance

---

# 📈 Model Evaluation

Model performance is evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* **Precision**
* **Recall**
* **F1-Score**

These metrics help measure how well the model predicts sentiment.

---

# 💬 Example Prediction

Example:

```python
predict_sentiment("This product is amazing")
```

Output:

```
Positive
```

Another example:

```python
predict_sentiment("This is the worst service ever")
```

Output:

```
Negative
```

---

# 💾 Model Saving

The trained model and vectorizer can be saved for reuse:

```python
import pickle

pickle.dump(model, open("model.pkl", "wb"))
pickle.dump(vectorizer, open("vectorizer.pkl", "wb"))
```

This allows the model to be **loaded later without retraining**.


---

# 👨‍💻 Author

**Anshul Srivastava**
 **Data Scientist Intern | Machine Learning Enthusiast**

Skills:

* Data Analysis
* Machine Learning
* Natural Language Processing
* Python

---



These **impress recruiters a lot on GitHub.**

