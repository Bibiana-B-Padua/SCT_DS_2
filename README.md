# SCT DataTrack Task 02 – Titanic EDA

🚢 This project performs **Exploratory Data Analysis (EDA)** on the famous Titanic dataset using Python (Pandas, Matplotlib, Seaborn).

## 📁 Project Structure

```
SCT_DataTrack_Task02/
├── data/
│   └── train.csv
├── visuals/
│   ├── Figure1.png
│   ├── Figure2.png
│   └── ...
├── titanic_eda.py
├── requirements.txt
└── README.md

```

---

## 🎯 Task Objective

- Clean and preprocess the dataset (`train.csv`)
- Handle missing values and irrelevant columns
- Create new features (e.g., `FamilySize`)
- Visualize and interpret patterns in survival rates

---

## 📊 Key Insights from EDA

| Feature       | Insight                                                 |
|---------------|----------------------------------------------------------|
| Gender        | Females had a higher chance of survival                  |
| Class         | 1st class passengers were most likely to survive         |
| Age           | Infants and children had better survival odds            |
| Embarked Port | Passengers from Cherbourg (C) survived more often        |
| Family Size   | Individuals with small families had better survival rates|

---

## ▶️ How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the script:
```bash
python titanic_eda.py
```

## 📦 Dependencies

- pandas
- matplotlib
- seaborn

## 📘 Dataset Source

- [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)

---
