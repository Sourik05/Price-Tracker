# Directory Overview

This folder contains two main directories:

1. Base_Model
2. Optimized_Model

---

## Directory Structure

Each directory follows a similar structure:
- `Model/`: Contains the model code in both `.py` (Python script) and `.ipynb` (Jupyter Notebook) formats.
- `Data/`: Contains the dataset used for training and evaluation.
- `Pkl/`: Contains the serialized files for the saved model (`best_rf_model.pkl`), TF-IDF vectorizer (`tfidf_vectorizer.pkl`), and label encoder (`label_encoder.pkl`).

---

## How to Run the Code

### Base Model
1. Navigate to the `Base_Model/Model/` directory in your terminal.
2. Run the base model script using the following command:
python intent_base.py

3. **Prediction**: To predict user input intents, use the `predict.py` script in the `Base_Model/` directory.

---

### Optimized Model
1. Navigate to the `Optimized_Model/Model/` directory in your terminal.
2. Run the optimized model script using the following command:
python intent_optimized.py
3. **Prediction**: To predict user input intents, use the `predict.py` script in the `Optimized_Model/` directory.

---

### Notes
- Ensure all dependencies are installed before running the scripts (e.g., `scikit-learn`, `nltk`, `joblib`).
- The `pkl/` directory contains essential files for inference. Do not modify or delete these files unless retraining the models.

---
