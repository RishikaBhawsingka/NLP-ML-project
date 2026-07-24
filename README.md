# NLP-ML-project
# 🧠 Human Behaviour Simulator using Machine Learning & BERT

## 📌 Project Overview

The **Human Behaviour Simulator** is a Natural Language Processing (NLP) project that predicts human emotions from text using multiple Machine Learning and Deep Learning models. The project compares traditional machine learning algorithms with a Transformer-based model (BERT) to identify the most effective approach for multi-class emotion classification.

The project follows a complete end-to-end machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, visualization, and documentation.

---

## 🎯 Objectives

- Predict human emotions from textual data.
- Compare traditional Machine Learning models with a Transformer-based model.
- Analyze model performance using multiple evaluation metrics.
- Build a reproducible NLP pipeline for emotion classification.

---

## 📂 Dataset

- **Dataset:** GoEmotions
- **Source:** Google Research
- **Training Samples:** 43,410
- **Validation Samples:** 5,426
- **Test Samples:** 5,427
- **Emotion Classes:** 28

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Hugging Face Transformers
- PyTorch
- Matplotlib
- OpenPyXL
- python-docx
- Google Colab

---

# 📊 Models Implemented

1. Logistic Regression
2. Naive Bayes
3. Random Forest
4. BERT (bert-base-uncased)

---

# 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|----------|-----------|--------|----------|
| Logistic Regression | 51.26% | 52.13% | 51.26% | 45.62% |
| Naive Bayes | 40.70% | 45.92% | 40.70% | 32.03% |
| Random Forest | 52.17% | 50.34% | 52.17% | 46.77% |
| **BERT** ⭐ | **58.72%** | **57.24%** | **58.72%** | **57.24%** |

---

# 📊 Visualizations

The project includes:

- Model Performance Comparison
- Confusion Matrix
- Classification Report
- Performance Analysis

---

# 📁 Project Structure

```text
HumanBehaviourSimulator/
│
├── datasets/
│
├── notebooks/
│
├── models/
│
├── plots/
│
├── reports/
│
├── Experiment_Log.xlsx
├── Project_Documentation.docx
├── requirements.txt
├── README.md
└── config.py
```

---

# 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/RishikaBhawsingka/HumanBehaviourSimulator.git
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the notebooks in order

1. Data Preprocessing
2. Data Cleaning
3. Logistic Regression
4. Naive Bayes
5. Random Forest
6. BERT

---

# 🏆 Results

Among all evaluated models, **BERT achieved the highest performance** by leveraging contextual word embeddings and attention mechanisms. Compared to traditional machine learning models using TF-IDF features, BERT demonstrated superior contextual understanding of language, leading to improved emotion classification performance.

---

# 🔮 Future Improvements

- Fine-tune RoBERTa and DeBERTa models.
- Perform hyperparameter optimization.
- Address class imbalance.
- Deploy the trained model as a web application.
- Integrate the emotion classifier into a real-time Human Behaviour Simulator.

---

# 👩‍💻 Author

**Rishika Bhawsingka**

B.Tech Computer Science Engineering

---

## ⭐ If you found this project useful, consider giving it a star!
