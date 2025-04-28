# Principles of Data Analytics

by Tihana Gray

## Setup

1. Sign up for a free GitHub account.
2. Go to the repository page in your browser.
3. Click the green Code button.
4. Click Create New Codespace on main.

## Technologies

- Python 3.x
- Git & GitHub
- Codespaces
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
---

# Tasks

# 🌸 Iris Data Analysis in Python (Jupyter Notebook)

This project explores the classic **Iris flower dataset** using **Pandas**, **Matplotlib**, **Seaborn**, and **NumPy**. The analysis is performed in a Jupyter Notebook and walks through common steps in exploratory data analysis (EDA).

---

## 📚 Dataset

- **Source**: [Iris Dataset on GitHub](https://gist.github.com/curran/a08a1080b88344b0c8a7)
- **Alternative**: `sklearn.datasets.load_iris()` — built-in in scikit-learn
- **Features**:  
  - `sepal_length`, `sepal_width`, `petal_length`, `petal_width`
  - `species` (categorical target with 3 classes)

---

## 🧪 Tasks and Explanations

### ✅ Task 1: Load the Dataset
- Imported the dataset using Scikit-learn's `load_iris()` function.
- Converted the data and feature names into a Pandas DataFrame.
- Added a new 'species' column by mapping the numeric target labels (0, 1, 2) to their real species names by using `pd.Series().map()`.
- 📖 [load_iris() Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html)

### ✅ Task 2: Explore the Structure
- Explored the structure of the dataset by checking its shape (rows and columns), printing the first and last 5 rows, and listing the feature names and target classes (species).
- Summarized the numerical data using `.describe()`, which calculated key statistics like mean, standard deviation, minimum, maximum, and quartiles for each flower measurement feature.

### ✅ Task 3: Summary Statistics
- Calculated mean, median, min, max, and standard deviation for each feature.
- Used `.describe()` and `.median()` functions from Pandas.

### ✅ Task 4: Feature Histograms
- Plotted histograms using Matplotlib.
- Added appropriate titles and axis labels.

### ✅ Task 5: Scatter Plot (Feature Relationship)
- Selected two features (`sepal_length` vs `petal_length`).
- Used Seaborn to color-code by species for visual classification.

### ✅ Task 6: Regression Line
- Used `numpy.polyfit()` to add a regression line.
- Overlaid line on scatter plot for linear relationship analysis.

### ✅ Task 7: Class Distributions with Box Plot
- Created box plots for `petal_length` across all three species.
- Visualised spread, median, and outliers.

### ✅ Task 8: Computing Correlations
- Used `.corr()` from Pandas to find correlations
- Displayed results using annotated heatmap with `Matplotlib`.

### ✅ Task 9: Simple Linear Regression
- Used Scikit-learn’s `LinearRegression()` to fit a regression model.
- Calculated the R² (coefficient of determination) using `r2_score`.
- Recreated the scatter plot and added a regression line and R² annotation.

### ✅ Task 10: Features
- Created a `pairplot` of the Iris dataset using `Seaborn` to visualise relationships between all feature pairs.
- The pairplot shows scatter plots for each feature combination and distributions for each feature along the diagonal.
- Points are color-coded by species, helping to identify patterns, correlations, and how easily the species can be separated based on their measurements.

---

## 🛠️ Technologies Used

- Python 3.x
- Git & GitHub
- Codespaces
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Results

This project demonstrates how basic data exploration and visualisation can help understand relationships and distributions in a well-structured dataset like Iris.

---

## 🔗 References

- [Iris Dataset - Wikipedia](https://en.wikipedia.org/wiki/Iris_flower_data_set)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Docs](https://matplotlib.org/)
- [Seaborn Docs](https://seaborn.pydata.org/)
- [NumPy polyfit](https://numpy.org/doc/stable/reference/generated/numpy.polyfit.html)
- [Scikit-learn Datasets](https://scikit-learn.org/stable/datasets/index.html)
- [Jupyter Notebook Docs](https://jupyter-notebook.readthedocs.io/en/stable/)


---



