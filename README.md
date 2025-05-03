# 🎬 IMDB Sentiment Analysis

This project performs sentiment classification on movie reviews from the IMDB dataset using Natural Language Processing (NLP). It includes thorough preprocessing, multiple vectorization techniques, and comparison of their impact on model performance.

___

## 📌 Project Overview

- **Goal**: Classify IMDB movie reviews as **positive** or **negative**.
- **Techniques**: Text cleaning, feature extraction (Count, Frequency, TF-IDF), and model evaluation.
- **Focus**: Understanding how different text representation methods affect classification performance.

---

## 🧹 Preprocessing Steps

We applied the following custom preprocessing functions:

- ✅ Remove special characters  
- ✅ Remove non-ASCII characters
- ✅ Remove punctuation  
- ✅ Convert text to lowercase    
- ✅ Replace numbers with text
- ✅ Trim whitespaces, Get Tokens  
- ✅ Remove stopwords  
- ✅ Lemmatize words and verbs

> Preprocessing code is implemented using Python, regex, and NLTK.

---

## ✍️ Text Representation Methods

We used three popular vectorization methods to represent text numerically:

- **Count Vectorizer**: Basic bag-of-words model  
- **Frequency (TF)**: Term frequency normalized  
- **TF-IDF**: Adjusts weights based on word rarity across documents  

---

## 📈 Results & Comparison

We tested each method with a classification model (e.g., Logistic Regression).  
**Findings:**

> In our experiments, we observed significant differences in performance among the three text representation methods Count, Frequency, and TF-IDF. **Frequency** consistently outperformed the others, it's avoiding over fitting. These results highlight the importance of choosing an appropriate representation method, as it can greatly influence classification performance depending on the nature of the dataset. Also at another project can found another way is the best.

## 📊 Model Performance

The following table shows the accuracy of ANN using different text representation methods:

| Vectorization Method | Accuracy |
|----------------------|----------|
| Count Vectorizer     | 86.1%    |
| Frequency (TF)       | 88.16%    |
| TF-IDF               | 85%    |

> Frequency provided the highest accuracy in our experiments.

---

## 🤖 Models Used

- ANN

