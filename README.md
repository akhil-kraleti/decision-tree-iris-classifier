# 🌸 Iris Flower Classification using Decision Tree Classifier

A Machine Learning project that classifies Iris flower species based on sepal and petal measurements using a Decision Tree Classifier with Post-Pruning. The model predicts whether a flower belongs to Iris-setosa, Iris-versicolor, or Iris-virginica.

## 📌 Project Overview

The Iris dataset is one of the most popular datasets in machine learning. This project focuses on:

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature relationship visualization
- Decision Tree model training
- Post-Pruning to reduce overfitting
- Model evaluation using classification metrics

## 🎯 Objective

To build a multi-class classification model capable of accurately predicting Iris flower species using four botanical measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## 📊 Dataset Information

- Total Samples: **3,000**
- Classes:
  - Iris-setosa
  - Iris-versicolor
  - Iris-virginica
- Balanced Dataset:
  - 1,000 samples per class

### Features

| Feature | Description |
|----------|-------------|
| Sepal Length | Length of sepal (cm) |
| Sepal Width | Width of sepal (cm) |
| Petal Length | Length of petal (cm) |
| Petal Width | Width of petal (cm) |

## 🔍 Exploratory Data Analysis

Performed:

- Statistical summary of features
- Missing value analysis
- Histograms for feature distribution
- Scatter plots for class separation
- Correlation matrix analysis

### Key Insights

- No missing values were found.
- Petal measurements provided better class separation than sepal measurements.
- Strong correlation observed between:
  - Petal Length and Petal Width
  - Sepal Length and Petal Length

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 🤖 Machine Learning Model

### Algorithm
- Decision Tree Classifier

### Training Configuration
- Train-Test Split: 70:30
- Maximum Tree Depth: 3
- Post-Pruning Applied

## 📈 Model Performance

| Metric | Score |
|----------|---------|
| Accuracy | **97.44%** |

### Classification Report

| Class | Precision | Recall | F1-Score |
|---------|-----------|---------|----------|
| Iris-setosa | 1.00 | 1.00 | 1.00 |
| Iris-versicolor | 0.92 | 1.00 | 0.96 |
| Iris-virginica | 1.00 | 0.93 | 0.96 |

## 📂 Project Structure

```text
Iris-Flower-Classification/
│
├── iris_synthetic_data.csv
├── Iris_Classification.ipynb
├── README.md
└── requirements.txt
```

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Iris-Flower-Classification.git
```

Navigate to the project directory:

```bash
cd Iris-Flower-Classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run all cells in:

```text
Iris_Classification.ipynb
```

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- Data preprocessing
- Exploratory Data Analysis
- Feature visualization
- Correlation analysis
- Decision Tree modeling
- Post-Pruning techniques
- Model evaluation and interpretation

## 👨‍💻 Author

**Akhil Tej Sarma Kraleti**

Computer Science Undergraduate | Machine Learning Enthusiast

---
⭐ If you found this project useful, consider giving it a star!
