# Sentiment Analysis in Python

This project performs **sentiment analysis** on text reviews using multiple NLP techniques,
ranging from traditional lexicon-based methods to state-of-the-art transformer models.

## 🚀 Techniques Used
- **VADER (NLTK)** – Lexicon & rule-based sentiment analysis
- **RoBERTa Transformer** – Pretrained deep learning model
- **Hugging Face Pipeline** – High-level sentiment inference

## 📊 Dataset
The dataset used contains text reviews with star ratings.

> ⚠️ The dataset file is **not included** in this repository.  
> Please place your dataset inside the `data/` folder.

Example:data/Reviews.csv

## 📁 Project Structure
/
├── notebooks/ # Jupyter notebooks (EDA & experiments)
├── src/ # Core source code
├── data/ # Dataset (ignored by git)
├── results/ # Output & visualizations
├── requirements.txt
└── README.md

## 🧠 Models
### 1. VADER
- Uses a bag-of-words approach
- Outputs: `neg`, `neu`, `pos`, `compound`

### 2. RoBERTa
- Transformer-based model
- Captures contextual meaning of text
- Model used:

