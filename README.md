# 💎 Advanced Statistical Analysis of Diamond Data

This project demonstrates rigorous hypothesis testing in Python by applying **one-way ANOVA**, **two-way ANOVA**, and **Tukey HSD post hoc** tests on diamond data from the Seaborn library. It explores how diamond prices vary across color grades and cut categories, and whether there are interaction effects between these factors.

## Datasets

- `diamonds.csv`  
  - **Source:** [Seaborn](https://seaborn.pydata.org/)  
  - **Observations:** 39,840 
  - **Contents:** Diamond prices across different color grades
- `diamonds2.csv`  
  - **Source:** [Seaborn](https://seaborn.pydata.org/)  
  - **Observations:** 34,935 
  - **Contents:** Diamond prices across different color grades and cut categories

## Technologies Used

- **Language**: Python
- **Environment**: Jupyter Notebook
- **Libraries**: `pandas`, `seaborn`, `statsmodels`

## Methods Applied

- **One-Way ANOVA**: Tests whether mean diamond prices differ across color grades.
- **Two-Way ANOVA**: Tests whether mean diamond prices differ across both color and cut, including their interaction.
- **Tukey HSD Post Hoc**: Performs pairwise comparisons of diamond color grades following one-way ANOVA.

## How to Run

1. Clone the repository or download the ZIP file from GitHub.
2. Open the project folder in your preferred environment.
3. Open `diamonds_anova_tukey.ipynb` and run the cells.

## Author

Developed by Juan Nathan.
