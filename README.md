# Fake News Detection: ML, LSTM, and DistilBERT

## Overview
This repository contains a complete workflow for fake news detection using three approaches:
1. **Logistic Regression (TF‑IDF baseline)**
2. **LSTM (deep learning sequence model)**
3. **DistilBERT (transformer fine‑tuning)**

The project demonstrates progression from classical machine learning to modern NLP, with unified evaluation metrics and visualizations.

## Dataset
- Source: Combined `Fake.csv` and `True.csv` datasets.
- Columns: `title`, `text`, `subject`, `date`.
- Labels: `0 = Fake`, `1 = Real`.

## Notebook Contents
- **Data Preparation:** Cleaning, labeling, train/test split.
- **Baseline Model:** Logistic Regression with TF‑IDF.
- **Deep Learning Model:** LSTM with embeddings, dropout, and EarlyStopping.
- **Transformer Model:** DistilBERT fine‑tuning using Hugging Face.
- **Evaluation:** Confusion matrices, ROC curves, accuracy/F1/AUC comparison.
- **Visualization:** Training vs validation curves, bar chart comparison.

## Results
| Model               | Accuracy | F1 Score | AUC  |
|----------------------|----------|----------|------|
| Logistic Regression  | ~0.91    | ~0.90    | ~0.92 |
| LSTM                 | ~0.93    | ~0.92    | ~0.94 |
| DistilBERT           | ~0.96    | ~0.95    | ~0.97 |

## How to Run

1. Open the notebook in Google Colab.
2. Upload the dataset (`Fake.csv`, `True.csv`).
3. Run cells sequentially to reproduce results.
4. Dataset.csv file link: https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets
5. Tools: Python, TensorFlow, Hugging Face Transformers, Scikit‑Learn, Plotly.
## Future Work
- Add multilingual fake news detection.
- Explore social media signals (likes, shares, retweets).
- Deploy as a Streamlit app for interactive testing.

- ## 👩‍💻 Author

*Zahabia Ahmed*  
Data Science Learner | Educator | Content Creator | Aspiring AI Engineer 
[YouTube: Zahabia Ahmed](https://www.youtube.com/@ZahabiaAhmed)
[Instagram](https://www.instagram.com/zahabiaahmed?igsh=MXkwNzkzdGJsMzJqOA==)
[FaceBook](https://www.facebook.com/share/1KBwSz91no/)
[X- Twitter]( https://x.com/AhmedZahabia?t=yAAjSTYTwRRQsXCeomBMuQ&s=08)
[Pinterest](https://pin.it/47OMFKosD)

###Feel free to contact me Zahabia Ahmed

---Stay Happy ,Keep Coding ---



