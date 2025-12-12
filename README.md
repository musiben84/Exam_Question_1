
# IMDb Sentiment Analysis – Classical ML, Deep Learning & RL Selector

This project implements an intelligent sentiment analysis system for IMDb reviews
using:
- Classical ML (e.g., Logistic Regression / SVM / Naive Bayes)
- Deep Learning (e.g., LSTM / GRU / CNN / DistilBERT)
- A Reinforcement Learning (RL) model selector that chooses between ML and DL per review.

The structure is designed for use with **Jupyter Notebooks in VS Code**.

## Project Structure

```text
imdb_sentiment_project/
├── data/
│   └── (you will download and extract the IMDb dataset here)
├── notebooks/
│   ├── 01_preprocessing_and_features.ipynb
│   ├── 02_classical_ml_model.ipynb
│   ├── 03_deep_learning_model.ipynb
│   └── 04_rl_model_selector.ipynb
├── reports/
│   └── Report_and_powerpoint_presentations
├── src/
│   ├── data_utils.py
│   ├── text_preprocessing.py
│   ├── ml_models.py
│   ├── dl_models.py
│   └── rl_selector.py
└── requirements.txt
```


