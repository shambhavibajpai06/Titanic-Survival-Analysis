Titanic Survival Analysis

This project analyzes the Titanic dataset to explore survival patterns and build predictive insights.

📌 Project Steps
1. Importing Libraries:

pandas, numpy for data handling

matplotlib, seaborn for visualization

2. Data Loading & Inspection:

Loaded dataset (Titanic-Dataset.csv)

Inspected structure, shape, and first few rows

3. Data Cleaning:

Handled missing values:

Numerical → imputed with median (e.g., Age, Fare)

Categorical → imputed with mode (Embarked, Sex)

Dropped high-cardinality columns with excessive missing values (Cabin)

4. Exploratory Data Analysis (EDA):

Visualized survival rates based on:

Gender (Sex)

Passenger class (Pclass)

Age distribution

Embarked port

Plotted histograms, bar plots, and count plots

5. Feature Engineering:

Created new features like FamilySize = SibSp + Parch

Binned continuous variables (Age groups)

6. Data Visualization:

Survival vs Non-survival distributions

Heatmaps for correlations

Class-wise and gender-wise insights

7. Model Preparation (Optional if included):

Encoded categorical variables

Split into train/test sets

Trained models (Logistic Regression, Decision Tree, etc.)

📂 Files

titanic_analysis.ipynb → Jupyter notebook with full analysis

Titanic-Dataset.csv → dataset used (from GFG datasets repo)

titanic_profiling_report.html → automated profiling report

🚀 How to Run

Clone this repository:

git clone https://github.com/shambhavibajpai06/Titanic-Survival-Analysis.git
cd Titanic-Survival-Analysis


Install dependencies:

pip install pandas numpy matplotlib seaborn ydata-profiling


Open the Jupyter notebook:

jupyter notebook titanic_analysis.ipynb

📊 Results & Insights:

-Women had higher survival rates than men.

-1st class passengers survived more often than 3rd class.

Children had better chances of survival compared to adults.
