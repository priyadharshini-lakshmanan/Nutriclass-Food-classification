Nutrition Food Data Analysis
----------------------------

This project analyzes a comprehensive food nutrition dataset using Python, pandas, and machine learning techniques. It covers data cleaning, preprocessing, outlier handling, and visualization for 31,700+ food records across 10 food types.
​


Dataset:

31,700 rows × 16 columns with nutrition metrics (Calories, Protein, Fat, Carbs, Sugar, Fiber, Sodium, Cholesterol, GlycemicIndex, WaterContent, ServingSize).
​

Food Types: 

Pizza (6000), 

Burger (5000), 

Donut (4500), 

Pasta (4000), 

Sushi (3500), 

Ice Cream (3000), 

Steak (2000), 

Apple (1500), 

Banana (1200),

Salad (1000).
​

Preprocessing: 

Handles 1.18% missing values, removes duplicates, caps outliers using IQR method, encodes categorical variables (IsVegan, IsGlutenFree).
​

Visualizations: 

Class distributions, count plots using matplotlib/seaborn.
​

Tech Stack:

Python with pandas, numpy, matplotlib, seaborn, scikit-learn

Jupyter Notebook for analysis and exploration
​

File Structure:

text

nutritionfooddata.ipynb  # Complete analysis notebook

Quick Start

Clone repository: git clone <repo-url>

Open nutritionfooddata.ipynb in Jupyter/Colab

Run all cells sequentially
​

Results

Clean dataset: 

31,260 rows after preprocessing

Outliers capped for reliable analysis

Ready for ML modeling (logistic regression, SVM, etc.)
​


