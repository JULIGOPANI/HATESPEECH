
# Hate Speech Detection

## Overview
This project focuses on detecting hate speech in social media content using machine learning and deep learning techniques. The project implements models such as **Random Forest**, **SVM**, and **LSTM** and addresses class imbalance using **SMOTE**. The **TF-IDF** technique is used for feature extraction, and the **LSTM** model achieved an accuracy of 89.7% with an F1 score of 0.94.

## Features
- Categorizes text into **Hate Speech**, **Offensive Language**, and **Neutral** categories.
- Implements data balancing using **SMOTE**.
- Extracts features using **TF-IDF**.
- Compares performance between traditional ML and DL models.
- Future-ready for incorporating transformer models like **BERT**.


## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hate-speech-detection.git
   cd hate-speech-detection

2. Install dependencies:
pip install -r requirements.txt

3. Prepare the dataset:
Place the dataset in the data/ folder or follow instructions in data/README.md.

4. Train the models:
python scripts/train_model.py

5. Test the models:
python scripts/run.py
