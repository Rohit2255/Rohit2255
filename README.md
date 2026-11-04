---
model_name: rohit-yadav-v1.0
license: open-to-collaboration
language: [en, hi]
library_name: human
pipeline_tag: data-science
base_model: jaunpur-uttar-pradesh
tags: [machine-learning, nlp, rag, genai, mlops, credit-risk, finance, trekking]
metrics: [f1, accuracy, chai-per-day]
model-index:
  - name: rohit-yadav-v1.0
    results: [amazon-reviews-sentiment-0.89, credit-card-fraud-0.9992]
---

<div align="center">

# 🧠 rohit-yadav-v1.0

### Model Card · Data Scientist · AI Engineer

`task: data-science` · `modalities: text, tabular, finance` · `status: fine-tuning on GenAI + MLOps`

[![Email](https://img.shields.io/badge/Contact-ry661432@gmail.com-1f6feb?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ry661432@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rohit_Yadav-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohit-kumar-yadav-b97360194/)
[![Kaggle](https://img.shields.io/badge/Kaggle-rohit2255-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/rohit2255)

</div>

---

## 📄 Model Description

**rohit-yadav-v1.0** is a data scientist fine-tuned on 3+ years of applied analytics, statistical modelling and production-minded AI work. Specialised in **NLP, RAG pipelines and financial ML**. Optimised for turning messy real-world data into decisions people can act on.

| | |
|---|---|
| **Developed by** | Rohit Yadav |
| **Base model** | Jaunpur, Uttar Pradesh (pre-trained on stubbornness) |
| **Fine-tuned in** | Mumbai → Gurgaon, India 🇮🇳 |
| **Model type** | Applied data scientist, human, multilingual (English, Hindi) |
| **Architecture** | Python-native · statistics-first · ships things |
| **Availability** | Open to AI / ML / Data Science roles |

---

## 🎯 Intended Use

**Direct use**
- Building ML and NLP pipelines end to end: cleaning, features, modelling, evaluation
- RAG systems and document Q&A with LangChain, FAISS and open LLMs
- Credit-risk, fraud, churn and sentiment modelling for finance
- Statistical modelling and rigorous code review for reproducibility

**Downstream use**
- Data / AI teams that need someone who reads the F1 score, not just the accuracy
- Collaboration on GenAI, MLOps and deep learning projects

**Out-of-scope use**
- Trading advice, astrology predictions, anything requiring zero chai

---

## 🏋️ Training Data

### Experience

| Period | Role | Org | What the model learned |
|---|---|---|---|
| Jun 2026 – Sep 2026 | Senior Associate, Data Science | **Innodata India** (Remote) | Statistical modelling · QC review of R/Statistics and Rust Q&A pairs · peer code review for reproducibility and correctness · standardised, error-categorised review reporting |
| Dec 2022 – Dec 2025 | Associate Analyst, Data & AI Integration | **RiseOTB** (Walmart Inc., Remote) | Data and AI integration in a large-scale retail environment |

### Education

| Degree | Institution |
|---|---|
| MCA (Master of Computer Applications) | Chandigarh University |
| B.Sc. Information Technology | Mumbai University |

---

## ⚙️ Training Procedure

### Core stack

```
Languages     →  Python · SQL · R · Bash
ML / Stats    →  scikit-learn · XGBoost · SMOTE · statistical modelling
NLP / GenAI   →  spaCy · NLTK · Gensim · LangChain · FAISS · Llama 3 · RAG
Deep Learning →  PyTorch · TensorFlow           (continued pre-training 🔄)
Deploy        →  Streamlit · Flask · Docker · Git · Linux
Data          →  Pandas · NumPy · Matplotlib · Seaborn · MySQL
```

### Training curriculum (public checkpoints)

| Checkpoint | Domain | What it does |
|---|---|---|
| [`Amazon-Review-Analysis`](https://github.com/Rohit2255/Amazon-Review-Analysis) | NLP | 50k reviews → cleaning, TF-IDF sentiment, LDA (8 topics), Word2Vec, spaCy NER |
| [`Stock-Market-Sentiment-Analyze`](https://github.com/Rohit2255/Stock-Market-Sentiment-Analyze) | NLP · Finance | Financial headline sentiment with XGBoost |
| [`Credit_Card_Fraud_Detection`](https://github.com/Rohit2255/Credit_Card_Fraud_Detection) | Fraud | Imbalanced classification with SMOTE |
| [`Customer_Churn_Prediction`](https://github.com/Rohit2255/Customer_Churn_Prediction) | Telecom | Logistic Regression and Random Forest, feature importance |
| [`credit_risk_scoring_system`](https://github.com/Rohit2255/credit_risk_scoring_system) | Credit risk | German Credit dataset, creditworthiness scoring |
| [`Buy-Now-Pay-Later-BNPL-Risk-Model`](https://github.com/Rohit2255/Buy-Now-Pay-Later-BNPL-Risk-Model) | Fintech | Borrower default prediction |
| [`NPA-Risk-Analysis-for-Bank-Loan-Portfolio`](https://github.com/Rohit2255/NPA-Risk-Analysis-for-Bank-Loan-Portfolio) | Banking | Non-performing asset risk analysis |

### GenAI projects

- **QuickCart AI chatbot** — RAG pipeline with LangChain, FAISS and Llama 3
- **Financial Document Q&A** — retrieval-augmented question answering over financial documents

---

## 📊 Evaluation Results

| Task | Dataset | Metric | Score |
|---|---|---|---|
| Review sentiment (binary) | Amazon Fine Food, 50k sample | Accuracy | **0.89** |
| — positive class | same | F1 | **0.93** |
| — negative class | same | F1 | **0.71** |
| Topic modelling (LDA) | same | Interpretable topics | **8 / 8** |
| Fraud detection | Credit Card Fraud | Accuracy | **0.9992** |
| Text preprocessing | Amazon reviews | Vocabulary reduction | **49.1%** |

> Evaluated with stratified 80/20 splits. Metrics are reported per class where the data is imbalanced.

---

## ⚠️ Limitations and Bias

- **Imbalanced data is the enemy.** A 99.92% accuracy on fraud means little without precision and recall, so I report F1 per class and try to fix the imbalance (SMOTE, `class_weight`) instead of hiding behind accuracy.
- **Known weakness:** the negative class in my own sentiment model (F1 0.71). I know why it happens and how to improve it.
- **Domain shift:** NER trained on news misreads food reviews. I always check whether a pre-trained model fits the domain before trusting it.
- **Currently under-trained on:** large-scale LLM fine-tuning, agents and production MLOps. These are active training areas.
- **Sleep-deprived inference:** performance degrades without chai.

---

## 🌍 Environmental Impact

- **Hardware:** one laptop, one chai kettle
- **Hours trained:** late nights and early mornings
- **Carbon emitted:** minimal, offset by regular Himalayan and Sahyadri trekking 🏔️ (Tungnath · Kedarkantha)

---

## 🚀 How to Get Started

```python
from rohit import DataScientist

rohit = DataScientist.from_pretrained("rohit-yadav-v1.0")

rohit.build(task="rag-pipeline", stack=["langchain", "faiss", "llama3"])
rohit.evaluate(metric="f1", per_class=True)   # never accuracy alone
rohit.ship(to="production")

rohit.contact("ry661432@gmail.com")
```

---

## 📈 Activity

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=Rohit2255&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rohit2255&layout=compact&langs_count=6&theme=github_dark&hide_border=true"/>

</div>

---

## 📚 Citation

```bibtex
@misc{yadav2026rohit,
  author       = {Yadav, Rohit},
  title        = {rohit-yadav-v1.0: A Data Scientist Fine-Tuned on Finance, NLP and RAG},
  year         = {2026},
  howpublished = {\url{https://github.com/Rohit2255}},
  note         = {Now fine-tuning on GenAI and MLOps}
}
```

---

## 🤝 Model Card Contact

Questions, collaborations or opportunities → **ry661432@gmail.com**

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=Rohit2255&color=1f6feb&style=flat-square&label=inference+requests)

*Model card last updated: 2026 · Version 1.0 · Training in progress*

</div>
