# BERT-Finetuning-IMDB
Fine-tuning BERT for sentiment analysis on the IMDB movie reviews dataset, including baseline model comparison and experimental analysis.

# BERT Fine-tuning on IMDB for Sentiment Analysis

##  Project Overview
This project reproduces the fine-tuning methodology from the research paper  
**“BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding” (Devlin et al., 2019)**  
and applies it to the **IMDB movie reviews dataset** for binary sentiment classification.

The goal is to evaluate BERT’s performance on long-form text data and compare it with a traditional baseline machine learning model.

---

##  Models Implemented
### **1. Baseline Model**
- TF-IDF Vectorizer  
- Logistic Regression  
- Evaluation using Accuracy, Precision, Recall, F1-score  

### **2. Main Model**
- Pre-trained **BERT (bert-base-uncased)**  
- Fine-tuned on IMDB dataset  
- Classification head added on top of BERT  
- Full end-to-end optimization

---

##  Contribution
As part of the course requirement, this project introduces a **significant methodological contribution** by:
- Implementing a baseline classical ML model  
- Comparing its performance against fine-tuned BERT  
- Conducting detailed error analysis and evaluation  

This contribution provides insights into the improvements gained through Transformer-based language representations.

---

## 📂 Repository Structure

BERT-Finetuning-IMDB/
│
├── notebooks/
│ └── BERT_IMDB_Sentiment_Analysis.ipynb
│
├── results/
│ ├── test-results.jpeg
│ ├── confusion_matrix.jpeg
| ├── metrics_summary.txt
│
├── requirements.txt
│
└── README.md


---

## ▶️ How to Run

### 1. Install 

pip install -r requirements.txt


### 2. Open the notebook

notebooks/BERT_IMDB_Sentiment_Analysis.ipynb


### 3. Run all cells

---

##  References
Devlin, J., Chang, M.-W., Lee, K., & Toutanova, K. (2019).  
**BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.**  
NAACL-HLT 2019.

Stanford IMDB Dataset: https://ai.stanford.edu/~amaas/data/sentiment/

