
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
│   └── report_template.md
├── src/
│   ├── data_utils.py
│   ├── text_preprocessing.py
│   ├── ml_models.py
│   ├── dl_models.py
│   └── rl_selector.py
└── requirements.txt
```

## How to Use in VS Code

1. Download this project folder (or the provided zip) to your machine.
2. Open the folder in **VS Code**.
3. Ensure you have Python 3.9+ installed.
4. Create and activate a virtual environment (optional but recommended).
5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
6. Open any notebook in the `notebooks/` folder and select your Python interpreter.
7. Follow the instructions in each notebook in order:
   1. `01_preprocessing_and_features.ipynb`
   2. `02_classical_ml_model.ipynb`
   3. `03_deep_learning_model.ipynb`
   4. `04_rl_model_selector.ipynb`

## Dataset

Download the **IMDb Large Movie Review Dataset** from:
https://ai.stanford.edu/~amaas/data/sentiment/

- Extract it under the `data/` directory, e.g.:
  - `data/aclImdb/train/`
  - `data/aclImdb/test/`

You will point your data loading code to this path in `01_preprocessing_and_features.ipynb`.

## Notes

- The notebooks contain **placeholders and TODOs** guiding you through the assignment.
- Use the markdown cells to document your decisions, evaluation metrics, and interpretations, especially for Part D.
