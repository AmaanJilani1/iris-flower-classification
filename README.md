# 🌸 Iris Flower — Exploratory Data Analysis & Feature Study

A structured **Exploratory Data Analysis (EDA)** project on the classic Iris dataset, investigating species differences, feature correlations, outliers, and the best features for classification — using Python, Scikit-learn, and Matplotlib.

---

## 📌 Project Overview

The Iris dataset contains measurements of 150 flowers across 3 species: *Setosa*, *Versicolor*, and *Virginica*. This project answers 6 analytical questions to understand how the four features — sepal length, sepal width, petal length, and petal width — differ across species and which features are most useful for distinguishing them.

---

## 🎯 Questions Answered

1. Which flower species has the largest average petal length?
2. Do sepal length and petal length appear correlated? Is it stronger for some species?
3. Which feature has the least overlap between species (best for classification)?
4. Are there any outliers in petal width — and which species do they belong to?
5. If you had to classify a new flower using only one feature, which would you choose and why?
6. Do flowers with shorter sepals tend to have narrower petals?

---

## 📊 Key Findings

| Question | Finding |
|----------|---------|
| **Largest petal length** | *Virginica* has the largest average petal length (~5.55 cm) |
| **Correlation** | Sepal and petal length are strongly correlated overall (r ≈ 0.87); strongest in *Versicolor* |
| **Best classifier feature** | Petal length — minimal overlap between species across boxplots |
| **Outliers in petal width** | *Setosa* contains outliers; *Versicolor* and *Virginica* are clean |
| **Single-feature classification** | Petal length (or petal width) — clearly separates *Setosa* from others |
| **Short sepals → narrow petals?** | Yes — positive correlation (r ≈ 0.82) confirmed between sepal length and petal width |

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3.x | Core programming language |
| Pandas | Data manipulation and groupby analysis |
| Scikit-learn | Loading the Iris dataset |
| Matplotlib | Scatter plots and boxplots |
| Jupyter Notebook | Interactive analysis environment |

---

## 📁 Repository Structure

```
iris-flower-classification/
│
├── IRIS_dataset.ipynb   # Main analysis notebook
└── README.md            # Project documentation
```

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/AmaanJilani1/iris-flower-classification.git
cd iris-flower-classification
```

**2. Install dependencies**
```bash
pip install pandas matplotlib scikit-learn jupyter
```

**3. Launch the notebook**
```bash
jupyter notebook IRIS_dataset.ipynb
```

> The dataset is loaded directly from Scikit-learn — no external file needed:
> ```python
> from sklearn.datasets import load_iris
> data = load_iris(as_frame=True)
> ```

---

## 📚 Dataset

- **Source:** Scikit-learn built-in (`sklearn.datasets.load_iris`)
- **Rows:** 150 samples (50 per species)
- **Features:** `sepal length (cm)`, `sepal width (cm)`, `petal length (cm)`, `petal width (cm)`
- **Target:** Species — *Setosa*, *Versicolor*, *Virginica*

---

## 👤 Author

**Amaan Jilani**  
[GitHub](https://github.com/AmaanJilani1) · [LinkedIn](https://www.linkedin.com/in/amaanjilani/)

---

