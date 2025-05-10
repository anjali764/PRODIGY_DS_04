![image](https://github.com/user-attachments/assets/fba69c8a-9558-4c7b-b1cd-bc36dddf243f)
# PRODIGY_DS_04
# 💬 Twitter Sentiment Analysis

This project was developed as part of my internship at **Prodigy InfoTech** under the domain of **Natural Language Processing (NLP)**. The primary objective was to analyze the sentiment of tweets using machine learning techniques to classify them as **positive**, **negative**, or **neutral**.

---

## 📁 Dataset

- The dataset (https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis) consists of tweets labeled with their respective sentiments.
- Each entry includes the tweet text and a sentiment label.
- Common preprocessing challenges included emojis, URLs, mentions, hashtags, and slang.

---

## 🧰 Tools & Libraries Used

- `Python`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `nltk`, `re`, `string`

---

## 🔄 Project Workflow

1. **Data Loading** – Imported the dataset and explored its structure.
2. **Text Preprocessing**:
   - Lowercasing
   - Removing stopwords, punctuation, URLs, mentions, hashtags
   - Tokenization and stemming
3. **Exploratory Data Analysis (EDA)**:
   - Word clouds and distribution plots
   - Visual inspection of class balance
4. **Vectorization** – Used `TF-IDF Vectorizer` to convert text into numerical format.
5. **Model Training** – Applied `Logistic Regression` for classification.
6. **Model Evaluation** – Evaluated using Accuracy Score, Confusion Matrix, and Classification Report.

---

## ✅ Key Learnings

- Efficient preprocessing techniques for raw Twitter data.
- Importance of balancing text data for sentiment analysis.
- Use of TF-IDF in transforming textual data into meaningful vectors.
- How Logistic Regression can be effectively used for NLP classification tasks.

---

## 📊 Output Metrics

- **Accuracy**: High accuracy on the test set.
- **Visuals**: Confusion Matrix and Word Clouds for positive, negative, and neutral tweets.

---

## 👤 Author

Internship Project – Twitter Sentiment Analysis  
By **Anjali Patwa**  
 Prodigy InfoTech
