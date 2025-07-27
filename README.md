# Twitter Sentiment Analysis using Naive Bayes

This project performs **sentiment analysis on Twitter data** using the **Naive Bayes algorithm**, built as part of a Machine Learning internship at **Pantech Pvt. Ltd.**. The notebook preprocesses tweets, applies TF-IDF vectorization, and evaluates sentiment classification performance using common metrics.

## 📌 Project Highlights

-  **Model Used**: Multinomial Naive Bayes
-  **Preprocessing**:
  
    - Tokenization
    - Stop word removal
    - Lemmatization
    - TF-IDF Vectorization
-  **Evaluation Metrics**:
    - Accuracy
    - Precision / Recall / F1 Score
    - Confusion Matrix
    - k-Fold Cross Validation
-  **Tools & Libraries**:
  - Python
  - Scikit-learn
  - Pandas
  - NLTK
  - Matplotlib / Seaborn (for visualization)

## File Description

- `Twitter_analysis.ipynb`: Main Collab Notebook with end-to-end pipeline for sentiment analysis.

##  Sample Workflow

1. Load dataset (CSV or scraped data)
2. Clean and preprocess tweets
3. Transform using TF-IDF
4. Train Naive Bayes classifier
5. Evaluate using confusion matrix and k-fold validation

##  Future Enhancements

- Try other classifiers (e.g., Logistic Regression, SVM)
- Use Word2Vec or BERT for embeddings
- Build a small web interface to input and classify tweets



