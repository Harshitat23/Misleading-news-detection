# Misleading-news-detection

**📌 Problem Statement**
With the rapid spread of misinformation, especially on social media detecting fake news has become increasingly difficult. The goal of this project is to build a machine learning model that can classify news articles as real or fake based on features extracted from the data.

**📂 Dataset**
The dataset contains:
1) title: Title of the news article.
2) news_url: URL of the article.
3) source_domain: Source domain that published the article.
4) tweet_num: Number of tweets or shares the article received.
5) real: Target variable indicating if the article is real (1) or fake (0).

**🔍 Objective**

-> Clean and preprocess the data.

-> Perform exploratory data analysis (EDA).

-> Build and evaluate machine learning models (Logistic Regression and Decision Tree).

-> Compare model performance and identify the better classifier.

**🧠 Model Building**
1. Logistic Regression
-> A linear model used for binary classification.
   
-> Good baseline model for text classification tasks.

3. Decision Tree Classifier
-> A non-linear model that builds decision rules based on the features.
   
-> Handles feature interactions well and provides interpretability.

**📊 Model Evaluation**
Metrics Used:
1) Accuracy Score
2) Confusion Matrix
3) Classification Report (includes Precision, Recall, F1-Score)
   
**Observations:**
-> Decision Tree outperformed Logistic Regression in terms of accuracy.

-> This suggests that a non-linear model is better suited for this dataset.
