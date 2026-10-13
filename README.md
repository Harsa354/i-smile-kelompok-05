# Phishing URL Classification Using Machine Learning

**Study Group I-Smile — EDA to Machine Learning | Group 5**

A machine learning project focused on analyzing URL-related features and classifying URLs as phishing or legitimate websites.

## 📌 About the Project

Phishing is a type of cyberattack that attempts to deceive users into visiting fraudulent websites or disclosing sensitive information. Analyzing URL characteristics can help identify patterns associated with potentially malicious websites.

This project explores a phishing URL dataset through Exploratory Data Analysis (EDA), data cleaning, preprocessing, and machine learning classification.

The primary objective is to build and evaluate a classification model that distinguishes phishing URLs from legitimate URLs using the available dataset features.

## 🎯 Project Objectives

- Explore the dataset and identify patterns related to phishing and legitimate URLs.
- Inspect data quality and prepare features for machine learning.
- Build a classification model using **K-Nearest Neighbors (KNN)**.
- Evaluate model performance using appropriate classification metrics.
- Interpret the results and discuss the model's limitations.

## 📊 Dataset

This project uses the **PhiUSIIL Phishing URL Website Dataset** from the UCI Machine Learning Repository.

- **Source:** [UCI Machine Learning Repository — PhiUSIIL Phishing URL Website Dataset](https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+website+dataset)
- **Dataset size:** 235,795 instances
- **Number of columns:** 56, including the target and identifier-related columns
- **Problem type:** Binary classification
- **Target variable:** `label`
  - `0` — Phishing
  - `1` — Legitimate

The dataset contains URL-related and webpage-related features that can be investigated during EDA and feature preparation.

The `FILENAME` column is an identifier-related field and will be reviewed before modeling. Feature selection and preprocessing decisions will be documented in the notebook.

## 🧪 Methodology

The project follows these stages:

1. **Exploratory Data Analysis (EDA)** — Examine dataset structure, descriptive statistics, target distribution, and relevant feature patterns.
2. **Data Cleaning** — Inspect missing values, duplicate records, data types, and other potential data-quality issues.
3. **Preprocessing** — Prepare suitable features for modeling, including encoding or selecting features where necessary and scaling numerical features for KNN.
4. **Data Splitting** — Separate training and testing data to evaluate generalization.
5. **Model Development** — Train a KNN classifier as the primary model and evaluate additional models if included in the experiment.
6. **Model Evaluation** — Assess performance using accuracy, precision, recall, a confusion matrix, and cross-validation where applicable.
7. **Conclusion** — Summarize the findings, model performance, and limitations.

All feature-selection and preprocessing decisions will be documented to reduce the risk of data leakage.

## 🤖 Machine Learning

The primary model is **K-Nearest Neighbors (KNN)**.

Feature scaling is important for KNN because the algorithm relies on distances between data points. Model selection and parameter tuning will be performed using the training data, with final evaluation on the held-out test set.

Additional models may be included for comparison if implemented and evaluated in the notebook.

## 📈 Results

*Results will be added after the experiments have been completed.*

This section will summarize the final model, evaluation metrics, key findings, and limitations based on the actual experimental results.

## 📁 Repository Structure

```text
i-smile-kelompok-05/
├── README.md
├── .gitignore
├── notebooks/
│   └── phishing_url_classification.ipynb
├── slides/
│   └── presentasi_project.pdf
└── docs/
    └── pembagian_tugas.md
```

*The structure above represents the planned organization. Files will appear as the project progresses.*

## ▶️ How to Run

1. Open the project notebook in Google Colab.
2. Access the dataset from its official source or the dataset-loading method documented in the notebook.
3. Run the notebook cells in order, or select **Runtime → Run all**.
4. Review the EDA visualizations, preprocessing steps, model evaluation, and conclusions.

Required Python libraries will be documented in the notebook once the implementation is finalized.

## 👥 Team Members

**Study Group I-Smile — Group 5**

| Member | Responsibility |
|---|---|
| Raihan Athallah | Project coordination and notebook integration |
| Ridho Darmawan | Data quality inspection and preprocessing |
| Mohammad Harsa Avava | Model development and evaluation |

*Responsibilities are provisional and should be updated to reflect the team's agreed task distribution and actual contributions.*

## 📚 References

- [PhiUSIIL Phishing URL Website Dataset — UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+website+dataset)
- Study Group I-Smile — EDA to Machine Learning learning materials.

---

*This repository documents the Group 5 mini-project for Study Group I-Smile: EDA to Machine Learning.*
