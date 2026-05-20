# 💳 Credit Card Fraud Detection

A Machine Learning project to detect fraudulent credit card transactions using classification algorithms on highly imbalanced financial transaction data.

---

## 📌 Project Overview

Credit card fraud is one of the major challenges in digital financial systems. Fraudulent transactions are extremely rare compared to legitimate ones, making this a highly **imbalanced classification problem**.

This project uses **Machine Learning techniques** to identify fraudulent transactions by analyzing historical transaction data and building predictive models capable of distinguishing fraud from legitimate activity.

The objective is to maximize fraud detection while minimizing false negatives, which are especially costly in financial systems.

---

## 🚀 Features

- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Handling highly imbalanced datasets
- Fraud vs non-fraud visualization
- Machine Learning model training
- Performance evaluation using classification metrics
- Confusion matrix analysis
- Fraud prediction pipeline

---

## 📂 Project Structure

```bash
Credit-Card-Fraud-Detection/
│── Credit_Card_Fraud_Detection.ipynb    # Main notebook
│── README.md                           # Project documentation
```

---

## 📊 Dataset Information

This project uses the **Credit Card Fraud Dataset** from Kaggle.

### Dataset Link

:contentReference[oaicite:1]{index=1}

### Dataset Characteristics

- **Transactions:** 1,000,000
- **Target Variable:** `is_fraud`
- **Problem Type:** Binary Classification
- **Nature:** Highly imbalanced fraud detection dataset
- **Dataset Type:** Simulated transaction behavior data

### Feature Description

| Feature | Description |
|--------|-------------|
| distance_from_home | Distance from transaction location to home |
| distance_from_last_transaction | Distance from previous transaction |
| ratio_to_median_purchase_price | Purchase amount ratio |
| repeat_retailer | Whether transaction occurred at a repeated retailer |
| used_chip | Whether chip was used |
| used_pin_number | Whether PIN was used |
| online_order | Whether transaction was online |
| fraud | Target variable (0 = Legitimate, 1 = Fraud) |

### Challenge

This dataset is **highly imbalanced**, meaning:

- Legitimate transactions dominate
- Fraudulent transactions are rare
- Accuracy alone can be misleading

Hence, metrics like **Recall, Precision, F1-score, ROC-AUC** become more important.

---

## 🛠 Technologies Used

- **Python**
- **Jupyter Notebook**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## ⚙️ Machine Learning Workflow

### 1. Data Loading
- Load transaction dataset
- Inspect structure and missing values

### 2. Exploratory Data Analysis
- Fraud vs legitimate transaction distribution
- Feature relationship analysis
- Correlation heatmaps
- Distribution plots

### 3. Data Preprocessing
- Feature scaling (if needed)
- Train-test split
- Handling imbalance

### 4. Model Training
Model used:

- **Random Forest Classifier**

### 5. Model Evaluation
Metrics used:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📈 Why Recall Matters More Than Accuracy

In fraud detection:

- Missing a fraud (**False Negative**) is very costly
- Flagging a normal transaction (**False Positive**) is less severe

So the model focuses more on:

✅ High Recall  
✅ Balanced Precision  
✅ Better fraud detection capability

---

## ▶️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/HariShankarLB/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
```

### Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```text
Credit_Card_Fraud_Detection.ipynb
```

---

## 📚 Dataset Source

This project uses the publicly available dataset from Kaggle:

:contentReference[oaicite:2]{index=2}

---

## ⭐ Support

If you found this project useful:

⭐ Star the repository    
📢 Share it with others

---

### “Detect fraud before fraud causes damage.”
