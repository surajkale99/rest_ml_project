# 🍽️ Restaurant Review Sentiment Analysis

## 📌 Project Overview

Many businesses fail due to lack of profit and insufficient improvement strategies. In the restaurant industry, understanding customer feedback is crucial for improving service quality and increasing profitability.

This project focuses on analyzing customer reviews using Machine Learning to identify whether a review is **positive** or **negative**. It helps restaurant owners understand customer sentiment and identify areas of improvement.

---

## 🎯 Objective

The main objectives of this project are:

* Analyze customer reviews of a restaurant
* Identify **positive and negative sentiments**
* Detect drawbacks such as disliked food items or poor service
* Help restaurant owners improve productivity and profitability

---

## 🧠 Problem Statement

Restaurant owners receive large volumes of text reviews, making manual analysis inefficient.

This project solves the problem by:

* Automatically classifying reviews into **positive** or **negative**
* Providing insights into customer satisfaction

---

## 📂 Dataset

The dataset contains restaurant reviews with sentiment labels.

**Columns:**

* `Review` → Customer review text
* `Liked` → 1 (Positive), 0 (Negative)

---

## ⚙️ Technologies Used

* Python
* Scikit-learn
* Natural Language Processing (NLP)
* Pandas & NumPy
* Matplotlib / Seaborn (optional)

---

## 🔍 Models Used

* Multinomial Naive Bayes
* Bernoulli Naive Bayes
* Logistic Regression

---

## 🛠️ Workflow

### 1. Data Preprocessing

* Remove punctuation
* Convert text to lowercase
* Remove stopwords
* Apply stemming

### 2. Feature Extraction

* Bag of Words (BoW)
* CountVectorizer / TF-IDF

### 3. Model Training

* Train models on training dataset
* Evaluate on test dataset

### 4. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Precision / Recall

---

## 📊 Expected Outcome

* Predict whether a review is **positive or negative**
* Identify customer dissatisfaction trends
* Help restaurant owners make data-driven decisions

---

## 🏆 Results

* In this study, an attempt has been made to classify sentiment analysis for restaurant reviews 
* using machine learning techniques. Two algorithms namely Multinomial Naive Bayes and 
* Bernoulli Naive Bayes are implemented.

* Evaluation metrics used here are accuracy, precision and recall.


* Using Multinomial Naive Bayes,
* Accuracy is  79.86 %
* Precision is  0.8
* Recall is  0.85


* Using Bernoulli Naive Bayes,
* Accuracy is  77.7 %
* Precision is  0.77
* Recall is  0.87


* Using Logistic Regression,
* Accuracy is  81.29 %
* Precision is  0.84
* Recall is  0.82


* From the above results, Logistic Regression is slightly better than Multinomial Naive Bayes

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/restaurant-sentiment-analysis.git

# Navigate to project folder
cd restaurant-sentiment-analysis

# Install dependencies
pip install -r requirements.txt

# Run the project
python main.py
```

---

## 📁 Project Structure

```
├── data/
│   └── Restaurant_Reviews.tsv
├── notebooks/
│   └── analysis.ipynb
├── models/
├── main.py
├── requirements.txt
└── README.md
```

---

## 💡 Future Improvements

* Use Deep Learning models (LSTM, BERT)
* Build a web dashboard
* Real-time review analysis
* Aspect-based sentiment analysis

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork and improve this project.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Your Name
