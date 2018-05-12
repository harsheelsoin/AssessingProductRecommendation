# Assessing Product Recommendation

The dataset consists of Women’s fashion online shop reviews, consisting of a title, a review text, and whether the review author would recommend the product. The goal is to determine whether a reviewer will recommend a product or not based on review title and review. Such a classifier can help find out what is good or bad about certain products or to highlight more relevant reviews (like a very critical and a very positive one) about certain products.

The code walks through five stages:

1. Data Loading and Pre-Processing
2. Basic Model Building and Evaluation (w & w/o GridSearchCV)
3. Feature Tuning using `Tfidf` Vectorizer & `Normalizer`+`CountVectorizer`
4. Using `n-grams` (word and character)
5. Evaluating Regularization Penalty

