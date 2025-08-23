# Exploratory-Data-Analysis-EDA-on-Iris-Dataset
🌸 Exploratory Data Analysis (EDA) on Iris Dataset
📌 Project Details

Project ID: #CC69855

Project Title: Exploratory Data Analysis (EDA) on Iris Dataset

Internship Domain: Data Science Intern (CodeClause Internship)

Level: Entry Level

🎯 Aim

Conduct exploratory data analysis (EDA) on the famous Iris dataset to understand its characteristics and relationships between features.

📊 Dataset

Source: https://raw.githubusercontent.com/uiuc-cse/data-fa14/gh-pages/data/iris.csv

Rows: 150

Columns: SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm, Species

🛠️ Technologies Used

Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook

🚀 Steps Performed

Import Libraries

Loaded Pandas, Matplotlib, Seaborn for analysis and visualization

Load Dataset

Used pd.read_csv("Iris.csv") to load the dataset

Data Overview

Checked structure, missing values, and summary statistics

Data Cleaning

Dropped unnecessary Id column

Exploratory Data Analysis (EDA)

Countplot → Species distribution

Histograms → Feature distributions

Boxplots → Detect outliers

Pairplot → Relationships between features

Heatmap → Correlation between features

GroupBy → Average feature values per species

📈 Key Insights

Each species (Setosa, Versicolor, Virginica) has 50 samples

Setosa has the smallest petals (short length & narrow width)

Virginica has the largest petals

Petal length and petal width are strongly correlated (0.96)

Sepal features are less useful for separating species

Petal features are better indicators of species classification

📎 How to Run

Install dependencies:

pip install pandas matplotlib seaborn jupyter


Open the Jupyter Notebook in VS Code or JupyterLab

Run cells step by step

🧠 What I Learned

How to load and clean datasets in Pandas

How to visualize data using Matplotlib & Seaborn

How to find relationships between features

Gained first experience in Exploratory Data Analysis (EDA)
