# 📌 Sentiment Analysis on Amazon Product Reviews


## 📖 Overview  
This project focuses on sentiment analysis of **Amazon product reviews** using **Natural Language Processing (NLP) and Machine Learning** techniques. The goal is to classify customer sentiments into positive, negative, or neutral categories based on their reviews.

## 📂 Dataset  
The dataset consists of Amazon product reviews, including text reviews and sentiment labels. Key features:  
- **Review Text**: Customer opinions about products  
- **Sentiment Labels**: Positive, Neutral, Negative  

## 🛠️ Methodology  
1. **Data Preprocessing**  
   - Text cleaning (lowercasing, punctuation removal, stopword removal, lemmatization)  
   - Tokenization and vectorization (`TF-IDF`, `CountVectorizer`, etc.)  
2. **Handling Class Imbalance**  
   - Techniques like **SMOTE** to balance classes  
3. **Feature Engineering**  
   - N-grams, Word embeddings  
4. **Model Training & Evaluation**  
   - Applied **Machine Learning models**:  
     - Logistic Regression  
     - Random Forest  
     - SVM  
     - Naïve Bayes  
     - XGBoost  
   - Performance Metrics: Accuracy, F1-score, Precision, Recall  

## 📊 Results  
- Achieved high accuracy using **[best performing model]**  
- Comparative evaluation of different models  
- Insights into customer sentiment trends  

## 🚀 Installation & Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Sentiment-Analysis-Amazon-Reviews.git
   cd Sentiment-Analysis-Amazon-Reviews
