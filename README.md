# 🛸 Spaceship Titanic - Machine Learning Classification

## 📘 Overview

This project is a solution to the [Kaggle Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic/overview) competition, which tasks participants with predicting whether a passenger was transported to another dimension during a fictional interstellar accident. Using a mix of numerical and categorical features, the goal is to build a robust classification model to predict the `Transported` status of passengers.

---

## 🧠 Problem Statement

The spaceship Titanic has met with a tragic fate, and many of its passengers have mysteriously disappeared — possibly teleported to another dimension. Your task is to use the given dataset to predict whether a passenger was transported.

---

## 🗂️ Project Structure

```

Spaceship-Titanic/
│
├── notebook/
│   └── spaceship-titanic.ipynb
├── README.md
├── requirements.txt
├── output/
│   └── submission.csv
├── dataset/
│   └── train.csv
│   └── test.csv
│   └── sample_submission.csv

```

---

## 🔍 Exploratory Data Analysis (EDA)

The notebook includes comprehensive EDA such as:

- Missing value analysis and imputation
- Distribution analysis of features
- Correlation and feature importance
- Encoding of categorical features (Label Encoding, One-Hot, etc.)

---

## 🛠️ Modeling Approach

Models and techniques used:

- **Tree-based Models**: XGBoost, LightGBM
- **Imputation**: `IterativeImputer`, `SimpleImputer`
- **Feature Engineering**: Cabin decomposition, Group-based features
- **Hyperparameter Tuning**: GridSearchCV or cross-validation
- **Evaluation Metric**: Accuracy on test set (binary classification)

---

## 📈 Results

- Achieved strong performance using tree-based ensemble models.
- Top features included `HomePlanet`, `CryoSleep`, `Cabin`, and `Shopping-related` behavior.
- Final model evaluated on Kaggle submission platform.

---

## 💡 Key Learnings

- Handling missing values effectively can significantly impact model performance.
- Feature engineering based on domain insights (e.g., deck from `Cabin`) adds valuable signal.
- Tree models like XGBoost are well-suited for mixed data types in classification tasks.

---

## 🚀 Getting Started

To run the notebook:

1. Clone the repo:

   ```bash
   git clone https://github.com/hifizhhh/Spaceship-Titanic.git
   cd spaceship-titanic
   ```

2. (Optional) Create and activate a virtual environment.

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

---

## 🙋‍♂️ Author

**Hafizh Syihabuddin Al Jauhar**  
Machine Learning & Data Science Enthusiast  
📧 [aljauhar.hafizh6@gmail.com](mailto:aljauhar.hafizh6@gmail.com) | 🌐 [LinkedIn](https://www.linkedin.com/in/hafizhsyihabuddinaljauhar/)

---

## 📝 License

This project is intended for educational and non-commercial use only.

```

```
