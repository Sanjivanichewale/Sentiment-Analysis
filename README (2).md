# Sentiment Analysis on IMDB Movie Reviews

A NLP project that classifies movie reviews as **Positive** or **Negative**.

## Details
- **Dataset:** IMDB Movie Reviews (HuggingFace)
- **Model:** TF-IDF + Logistic Regression
- **Accuracy:** 83.30%
- **Language:** Python 3.12

## Libraries
`spaCy` `scikit-learn` `pandas` `matplotlib` `seaborn` `wordcloud` `HuggingFace datasets`

## How to Run

```bash
pip install scikit-learn spacy datasets matplotlib seaborn wordcloud
python -m spacy download en_core_web_sm
```

Open `task2.ipynb` in Jupyter and run all cells top to bottom.

## Results

| Class | Precision | Recall | F1-Score |
|---|---|---|---|
| Negative | 0.85 | 0.82 | 0.83 |
| Positive | 0.82 | 0.85 | 0.83 |

## Author
**Sanjivani Chewale** — Internship Project, April 2026
