# 📜 Sentiment Analysis using LSTM (Kaggle Dataset)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This repository contains a **Sentiment Analysis Model** using **LSTM (Long Short-Term Memory)** on the **Kaggle Sentiment Analysis Dataset**.  
The model classifies reviews as **Positive**, **Negative**, or optionally **Neutral**.

The project includes:
- Training an LSTM model on Kaggle sentiment dataset
- Saving the trained model and tokenizer
- Running predictions on single reviews or batch CSVs
- Support for **Google Colab** and local execution

---

## 🔹 Features

- Deep Learning-based **LSTM model**
- Tokenization and padding for text preprocessing
- Single review prediction
- Colab-ready workflow
- Optional 3-class sentiment support (Positive / Negative / Neutral)

---

## 📁 Repository Structure
```bash
├── Dataset
|    ├── test.csv
|    └── train.csv
├── sentiment_analysis.ipynb   # Colab notebook to train the model
├── tw.keras                   # Trained LSTM model (after training)
├── requirements.txt           # Python dependencies
└── README.md
```

---

## 🗂 Dataset

- Dataset: [Kaggle Sentiment Analysis Dataset](https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset?select=train.csv)  
- CSV columns include:
  - `text` → The review text
  - `label` → Sentiment label
    - 0 → Negative  
    - 1 → Positive  
    - Optional 2 → Neutral (if extended)
- Place the CSV file in the project folder or upload to Colab

---

## 🛠 Installation

### 1. Local Setup

```bash
git clone https://github.com/yourusername/Sentiment-Analysis.git
cd Sentiment-Analysis
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

---

## Google Colab Setup
```bash
!pip install tensorflow scikit-learn pickle5 pandas
```

---

## 🚀 Training the Model

- Load train.csv into the notebook.
- Preprocess text: tokenization and padding
- Convert labels to integers (0,1,2 for neutral if used)
- Train LSTM model
- Save tw.keras
- Test a sample prediction in the notebook

---

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🤝 Contributing
Feel free to contribute by submitting a pull request or reporting issues!

---

## 📩 Contact
📧 Email: [ramnrngupta@gmail.com](mailto:ramnrngupta@gmail.com)
📌 Linkedin: 
[Ram Narayan Gupta](https://linkedin.com/in/ram-narayan-gupta)