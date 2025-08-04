# 🧠 Titanic Data Preprocessing – Task 1 (AI/ML Internship)

**Author:** sudhatanmai  
**Repository Link:** [https://github.com/sudhatanmai/titanic-data-preprocessing](https://github.com/sudhatanmai/titanic-data-preprocessing)

---

## 🎯 Objective

To clean and prepare the Titanic dataset for Machine Learning by performing:
- Handling missing values
- Encoding categorical variables
- Normalizing features
- Visualizing and removing outliers

---

## 📁 Repository Contents

| File Name              | Description                                         |
|------------------------|-----------------------------------------------------|
| `Titanic-Dataset.csv`  | Raw dataset used for preprocessing.                 |
| `titanic_preprocessing.py` | Python script used for cleaning and preprocessing the dataset. |
| `processed_titanic.csv`| Final cleaned and processed data.                  |
| `boxplot_outliers.png` | Boxplot showing outliers in `Age` and `Fare` columns. |
| `README.md`            | This file.                                          |

---

## 🔧 Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **sklearn.preprocessing**

---

## 📝 Steps Followed

1. **Load & Inspect the Data**
   - Displayed first 5 rows
   - Checked data types and null values

2. **Handle Missing Values**
   - Filled `Age` with median
   - Filled `Embarked` with mode
   - Dropped `Cabin` due to too many missing values

3. **Encode Categorical Data**
   - Used label encoding on `Sex`
   - Used one-hot encoding on `Embarked`

4. **Normalize Data**
   - Standardized `Age` and `Fare` columns using `StandardScaler`

5. **Visualize Outliers**
   - Used boxplots for `Age` and `Fare`
   - Saved as `boxplot_outliers.png`

---

## 📊 Output Example

> ![Boxplot of Outliers](boxplot_outliers.png)

---

## ✅ Outcome

- Cleaned and ready dataset stored in `processed_titanic.csv`
- Useful for training ML models

---

## 📌 Submission Link

👉 [https://github.com/sudhatanmai/titanic-data-preprocessing](https://github.com/sudhatanmai/titanic-data-preprocessing)

