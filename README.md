<<<<<<< HEAD

# Sentiment Analysis Dataset on Patrick Kluivert as Indonesian National Football Coach

This repository contains preprocessed tweet datasets collected from Twitter in relation to the public response toward the appointment of Patrick Kluivert as the head coach of the Indonesian national football team (January–May 2025). The datasets are provided in two sentiment formats: binary (positive vs. negative) and three-class (positive, neutral, negative) classification.

## 📁 Dataset Files

- `tweets_2class.csv`:  
  Cleaned and labeled tweets for binary sentiment classification. Each entry is labeled as `positive` or `negative`.

- `tweets_3class.csv`:  
  Cleaned and labeled tweets for three-class sentiment classification. Each entry is labeled as `positive`, `neutral`, or `negative`.

All files are encoded in UTF-8 with BOM to ensure compatibility with Indonesian characters.

## 🧹 Preprocessing Steps

Each tweet has been processed through the following pipeline:
- Duplicate removal
- Lowercasing and normalization
- Removal of URLs, mentions, hashtags, emojis, digits, and punctuation
- Slang word replacement using a custom slang dictionary
- Normalization of emotional expressions (e.g., "waaah" → "wah")
- Stopword filtering and possessive suffix removal
- Stemming using [Sastrawi](https://github.com/har07/PySastrawi)
- TF-IDF feature preparation (not included in dataset, only raw text + labels)

## 🧠 Labeling

Sentiment labels were generated using a pre-trained Indonesian RoBERTa-based sentiment model (`w11wo/indonesian-roberta-base-sentiment-classifier`) with manual refinement.

## 🔗 Citation

If you use this dataset in your research, please cite the following work (or this GitHub page):

```
A. G. Ghifari, G. Y. Ananada, & K. Purwandari. (2025). A Comparative Sentiment Analysis of Public Opinion on Indonesia’s National Football Coach Using CRNN and SVM.
```

## 📜 License

This dataset is provided for research and academic use only.

---

If you have any questions, feel free to contact us via GitHub Issues.
=======
# dataset_sentiment_analysis_indonesia_coach
>>>>>>> 36368312c5014fd5c2dc49773f04c3f41c187b3e
