# 🌳 AI Lab 3 — Movie Recommendation using Decision Trees

This notebook implements a simple **decision tree classifier** trained on movie metadata and user ratings.  
It is part of the Artificial Intelligence course and focuses on symbolic learning using scikit-learn.

---

## 🧠 Objectives

- Preprocess and clean movie metadata and ratings data
- Extract categorical and numerical features relevant to user preferences
- Train a Decision Tree classifier to predict if a user would rate a movie as "liked"
- Evaluate model accuracy and interpret decision rules

---

## 📂 Files Included

- `AI_23_decision_trees_Student_Version.ipynb`: Jupyter notebook with the full pipeline
- `movies_metadata.csv`: Movie information (title, genres, runtime, etc.)
- `ratings.csv`: User ratings dataset used to define the binary target variable

---

## 📊 Features

- Uses Pandas for data wrangling
- Maps continuous ratings into binary classes ("liked" vs "not liked")
- Extracts genre, runtime, and popularity as features
- Builds a decision tree using `scikit-learn`
- Visualizes tree structure and evaluates performance

---

## 🛠️ Technologies Used

- Python 3
- Pandas, NumPy
- scikit-learn
- Matplotlib (for tree visualization)
- Jupyter Notebook

---

## ▶️ How to Run

```bash
pip install pandas numpy scikit-learn matplotlib
