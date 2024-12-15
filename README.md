# Sentiment-Analysis-of-Amazon-products

# 1. Data Cleaning
 - Removed HTML tags using regular expressions.
 - Expanded contractions (e.g., "don't" to "do not") for better processing.
 - Removed punctuation to simplify text analysis.
 - Converted all text to lowercase for uniformity.

## 2. Tokenization
# - Removed stopwords (e.g., "the", "is", "and") that do not contribute to sentiment.
# - Applied lemmatization to reduce words to their base form (e.g., "running" to "run").
# - Created word clouds to visualize frequent words in positive and negative reviews.

## 3. Vectorization
# - Transformed text data into numerical format using TF-IDF (Term Frequency-Inverse Document Frequency).

## 4. Model Training
# - Trained models using:
#   - Random Forest Classifier
#   - Logistic Regression
#   - Naive Bayes Classifier

## 5. Model Evaluation
# - Evaluated model performance using accuracy metric.
# - Compared models to determine the best-performing classifier for sentiment prediction.

