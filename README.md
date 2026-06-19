This is demo
# Fake News Detection using Machine Learning

This project classifies news as **Real** or **Fake** using Machine Learning and NLP techniques.

## Features
- Data Cleaning & Preprocessing
- Text Vectorization using TF-IDF
- Model Training and Evaluation

## Dataset
- **Dataset:** Fake and Real News Dataset (George McIntire)
- **Source:** [GitHub - GeorgeMcIntire/fake_real_news_dataset](https://github.com/GeorgeMcIntire/fake_real_news_dataset)
- **Columns:** title, text, label (REAL/FAKE)

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn (Logistic Regression)
- NLP, TF-IDF
- Google Colab

## How to Run
1. Install dependencies:
```bash
   pip install pandas numpy scikit-learn
```
2. Open `Fake_News_Detection.ipynb`
3. Run all cells sequentially — the dataset loads automatically from the source URL

## Results
- Achieved **95% accuracy** on the test set using Logistic Regression with TF-IDF features
- Evaluated using a confusion matrix to assess REAL vs FAKE classification performance
