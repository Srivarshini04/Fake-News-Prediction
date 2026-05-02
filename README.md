# 📰 Fake News Prediction using Machine Learning

## 📌 Overview

This project builds a **machine learning model** to classify news articles as **Fake** or **Real** using **Natural Language Processing (NLP)** techniques.

The system processes raw news text, converts it into numerical features using **TF-IDF**, and applies a **Logistic Regression model** for classification.

---

## 🚀 Key Features

* Text preprocessing using:

  * Lowercasing
  * Removing special characters
  * Stopword removal (NLTK)
  * Stemming (Porter Stemmer)
* Feature extraction using **TF-IDF Vectorizer**
* Model training using **Logistic Regression**
* Model evaluation using **accuracy score**
* Predictive system for testing new news input

---

## 🛠️ Tech Stack

* **Language:** Python

* **Libraries:**

  * Pandas
  * NumPy
  * Scikit-learn
  * NLTK

* **Tools:**

  * Google Colab
  * Jupyter Notebook

---

## 📂 Dataset

* The dataset contains news articles labeled as:

  * `0 → Real News`
  * `1 → Fake News`

* Features used:

  * News text content

---

## ⚙️ Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Preprocessing

   * Removing punctuation
   * Stopword removal
   * Stemming
4. Splitting data into training and testing sets
5. Feature extraction using **TF-IDF**
6. Model training using **Logistic Regression**
7. Model evaluation using accuracy score
8. Building a predictive system

---

## 📊 Model Performance

* The model is evaluated using **97.7%** accuracy score on test data
* Provides reliable classification for fake vs real news


---

## 🔍 Sample Prediction

```python
X_new = X_test[1]
prediction = model.predict(X_new)

if(prediction[0] == 0):
    print("The News is Real")
else:
    print("The News is Fake")
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/Srivarshini04/fake-news-prediction.git
```

2. Install required libraries:

```bash
pip install numpy pandas scikit-learn nltk
```

3. Run the notebook:

* Open `.ipynb` file in **Jupyter Notebook** or **Google Colab**

---

## 💡 Future Improvements

* Use advanced models like:

  * LSTM
  * BERT
* Improve dataset size for better accuracy
* Deploy as a web application
* Add real-time news verification

---

## 🙋‍♀️ Author

**Srivarshini Komirishetty**

* GitHub: https://github.com/Srivarshini04
* LinkedIn: https://linkedin.com/in/srivarshini-komirishetty

---

## ⭐ Conclusion

This project demonstrates how machine learning and NLP can be effectively used to detect fake news and combat misinformation.

---

## 📜 License

This project is open-source and available under the MIT License.
