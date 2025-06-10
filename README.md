#  Cyber Bully Detection using Machine Learning

A Natural Language Processing (NLP) project that detects cyberbullying in text data such as social media posts, comments, and messages. This tool can be used to automatically flag offensive or harmful content to create a safer online environment.

---

##  Project Overview

Cyberbullying has become a growing concern in the digital age. This project aims to build a classifier that detects bullying content in user-generated text using machine learning and NLP techniques.

---

##  Dataset

- **Source**: Kaggle / Twitter / Custom labeled dataset  
- **Format**: CSV with columns like:
  - `text` – the actual message/post  
  - `label` – 0 for non-bullying, 1 for bullying  
- **Preprocessing Includes**:
  - Lowercasing  
  - Removing punctuation, stopwords, URLs  
  - Tokenization and Lemmatization

---

##  Technologies Used

- Python   
- Jupyter Notebook  
- NLP: NLTK / spaCy  
- Scikit-learn  
- WordCloud, Seaborn, Matplotlib  
- Flask (for deployment)  
- HTML/CSS (UI)

---

##  ML Workflow

1. **Text Preprocessing**  
   - Clean and tokenize text  
   - Remove stopwords and apply lemmatization  
2. **Feature Extraction**  
   - TF-IDF Vectorization  
3. **Model Training**  
   - Logistic Regression, Naive Bayes, Random Forest, SVM  
4. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1 Score, Confusion Matrix  
5. **Deployment**  
   - Flask-based web interface for live bullying text detection

---

# Web App Features
Input a sentence or comment in a text box

Click "Detect" to get instant prediction

Displays whether the content is bullying or safe

Clean and responsive interface

# Results
Best performance with Logistic Regression and SVM

# Accuracy achieved: ~90%

Balanced precision and recall to minimize false positives/negatives

