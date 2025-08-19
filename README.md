# Sentiment Analysis of Student Reviews & LSTM Next-Word Prediction

This project covers two parts:

1. **Sentiment Analysis of Post-Training Student Reviews**
   - Built and compared multiple ML/DL models: Random Forest, XGBoost, Naive Bayes, SVM, LSTM, Transformers.
   - Improved accuracy and extracted insights from reviews to help improve training quality.

2. **Next-Word Prediction Model (Language Modeling)**
   - Implemented an LSTM-based next-word predictor on a custom text corpus (~50,000+ tokens) built from a Wikipedia sample dump.
   - Achieved ~60% accuracy after 10 epochs with tokenization and sequence padding.

## Setup Instructions

1. Clone the repo
   ```bash
   git clone https://github.com/your-username/student-reviews-sentiment-analysis.git
   cd student-reviews-sentiment-analysis
   ```

2. Install requirements
   ```bash
   pip install -r requirements.txt
   ```

3. Run Jupyter notebooks from `notebooks/` to reproduce results.

## Dataset

- **Student Reviews**: `data/reviews.csv` (synthetic dataset created for demonstration).
- **Wikipedia Corpus**: `data/wikipedia_sample.txt` (subset of Wikipedia dump).

## Models Used

- Traditional ML: Random Forest, XGBoost, Naive Bayes, SVM
- Deep Learning: LSTM for sentiment classification and next-word prediction
- Transformers: Pre-trained BERT for sentiment analysis
