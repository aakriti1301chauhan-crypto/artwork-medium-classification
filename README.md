# artwork-medium-classification
End-to-end ML project using NLP (TF-IDF) and Random Forest for artwork medium classification with feature engineering.

This project focuses on classifying the medium of artworks using machine learning techniques. The dataset includes textual descriptions, captions, and structured metadata.

## Approach

- Combined multiple text fields (title, description, caption)
- Applied text preprocessing and cleaning
- Used TF-IDF for text vectorization (NLP)
- Engineered features such as area and keyword indicators
- Trained multiple models:
  - Logistic Regression
  - Random Forest
  - XGBoost

## Results

- Random Forest achieved the best performance with ~96% accuracy
- The model effectively captured patterns in textual and structured data

## Key Learnings

- Importance of NLP in text-heavy datasets
- Feature engineering significantly improves performance
- Ensemble models outperform linear models in complex tasks

## Tech Stack

- Python
- Scikit-learn
- Pandas, NumPy
- TF-IDF (NLP)

💡 This project demonstrates a complete machine learning pipeline from data preprocessing to model evaluation.
## Results
Logistic Regression: 14.25%
Random Forest: 96.37%
XGBoost: 96%
