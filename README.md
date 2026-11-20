# Iris Flower Exploratory Data Analysis (EDA)

**Author:** Rohit Agarwal  
**Program:** HCLTech Data Analysis Training Project  

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the classic **Iris Flower Dataset** to understand the distribution, statistical properties, and relationships among different flower species (`Iris-setosa`, `Iris-versicolor`, and `Iris-virginica`).

## 🛠️ Tools & Libraries Used
* **Python**
* **Pandas** (Data manipulation, grouping, and filtering)
* **NumPy** (Numerical and statistical calculations)
* **Matplotlib** (Data visualization)
* **Google Colab** (Development environment)

## 📂 Repository Contents
* `Rohit_Agarwal_Iris_EDA.ipynb`: Complete Jupyter/Colab notebook containing all code, analysis, charts, and observations.
* `iris_clean.csv`: Cleaned dataset with proper column headers (`sepal_length`, `sepal_width`, `petal_length`, `petal_width`, `species`).

## 🔍 Key Tasks Performed
1. **Data Inspection:** Checked dataset dimensions, data types, summary statistics, missing values, and duplicate records.
2. **Species Distribution:** Verified record counts for each iris species.
3. **Statistical Analysis:** Calculated mean, median, minimum, and maximum values for sepal and petal dimensions using NumPy and Pandas `groupby()`.
4. **Filtering & Sorting:** Identified the top 5 flowers with the largest petal lengths and filtered records based on specific measurements.
5. **Data Visualization:** Created a Species-Count Bar Chart and a Petal-Length Distribution Histogram.

## 💡 Key Observations
1. **Balanced Dataset:** The dataset contains 150 total rows, equally distributed across three species (`Iris-setosa`, `Iris-versicolor`, and `Iris-virginica`) with 50 samples each.
2. **Species Comparison:** `Iris-virginica` has the highest average `petal_length` (5.55 cm) and `petal_width` (2.03 cm), whereas `Iris-setosa` has the smallest petal measurements.
3. **Data Quality:** There are no missing (null) values in any column, though the dataset contains 3 duplicate rows.
4.
