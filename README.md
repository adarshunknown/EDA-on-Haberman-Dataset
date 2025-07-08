# EDA-on-Haberman-Dataset
# 📊 EDA on Haberman's Survival Dataset

This project performs **Exploratory Data Analysis (EDA)** on the Haberman's Survival dataset, which contains data on breast cancer patients who had undergone surgery. The goal is to uncover insights into the survival rates and the impact of various features.

---

## 📁 Project Files

- `eda on haberman.ipynb` – The complete Jupyter notebook for EDA
- `README.md` – Project documentation

---

## 📦 Dataset Information

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Haberman%27s+Survival)
- **Features**:
  - `Age`: Age of patient at the time of surgery
  - `Year`: Year of surgery (year - 1900)
  - `Nodes`: Number of positive axillary lymph nodes detected
  - `Survival_Status`:  
    - `1` → survived 5 years or longer
    - `2` → died within 5 years

---

## 🔍 Objectives of EDA

- Understand distribution of features (age, year, nodes)
- Check for skewness and kurtosis (normality of data)
- Visualize survival trends and patterns
- Identify correlations and potential outliers
- Evaluate feature relationships with target variable (`Survival_Status`)

---

## 📈 Key Analyses Performed

- ✔️ Univariate Analysis (Histograms, Boxplots)
- ✔️ Bivariate Analysis (Pairplots, Violin plots)
- ✔️ Multivariate Analysis
- ✔️ Skewness & Kurtosis interpretation
- ✔️ Heatmap of correlation matrix
- ✔️ Class balance & survival trend analysis

---

## 🛠️ Technologies Used

- Python (Jupyter Notebook)
- `Pandas`, `NumPy` – data manipulation
- `Matplotlib`, `Seaborn` – visualization
- `SciPy` – statistical computations

---

## 📊 Summary of Findings

- **Age** and **year of operation** are fairly symmetric (low skew).
- **Number of nodes** is right-skewed and has some outliers.
- Survivors tend to have **fewer positive nodes**.
- Survival status is **imbalanced** (more patients survived).
- No strong correlation among features, suggesting they are mostly independent.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone  https://github.com/adarshunknown/EDA-on-Haberman-Dataset.git
   cd haberman-eda
