**Objective**

Perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract meaningful insights, identify trends, and visualize relationships between different features.

**Dataset**

* **Source:** [Kaggle – Titanic Dataset](https://www.kaggle.com/c/titanic/data)
* **File Used:** `train.csv`
* **Rows:** 891
* **Columns:** 12 (Passenger details, ticket info, survival status, etc.)

**Tools & Libraries Used**
* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook (via VS Code)

** Steps Followed**

1. **Data Loading & Basic Exploration**

   * Loaded dataset using Pandas.
   * Checked data types, null values, and basic statistics.

2. **Univariate Analysis**

   * Count plots for categorical features (`Survived`, `Sex`, `Pclass`).
   * Histograms for numerical features (`Age`, `Fare`).

3. **Bivariate Analysis**

   * Compared survival rates across gender, class, and age.
   * Scatter plots to analyze relationships between `Age`, `Fare`, and `Survival`.

4. **Correlation Analysis**

   * Generated a heatmap for numeric columns to identify strong correlations.

5. **Observations & Insights**

   * Added Markdown cells with analysis for each visualization.

**Key Insights**

* Majority of passengers did not survive.
* Females had a higher survival rate than males.
* First-class passengers survived more often than second and third class.
* Younger passengers had slightly better chances of survival.
* Higher fares were generally associated with better survival odds.

---

**Files in This Repository**

* `EDAtask4.ipynb` – Jupyter Notebook with code, plots, and observations.
* `EDAtask4.pdf` – Exported PDF version of the analysis.
* `train.csv` – Titanic dataset.
* `README.md` – Project documentation (this file).

**Outcome**

This task provided practical experience in:

* Performing data exploration.
* Creating visualizations.
* Writing concise observations from plots.
* Summarizing findings effectively.

