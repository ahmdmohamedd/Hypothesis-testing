# Hypothesis Testing with Python

## Overview
This project demonstrates various hypothesis testing techniques using Python, including:
- **t-test**: To compare the average ages of male and female passengers.
- **ANOVA (Analysis of Variance)**: To test for differences in average age across passenger classes (First, Second, and Third).
- **Wilcoxon Signed-Rank Test**: To compare paired samples of passenger ages before and after a simulated event.

Each test shows statistically significant results, rejecting the null hypothesis at a 5% significance level.

## Dataset
The **Titanic** dataset, available through Seaborn, is used in this project. It contains information about passengers, including age, sex, and class. For the Wilcoxon Signed-Rank test, we simulate paired data.

## Tests Performed
### 1. **t-test**
- **Hypothesis**: Is there a significant difference between the average ages of male and female passengers?
- **Result**: The p-value is less than 0.05, so we reject the null hypothesis, indicating a significant difference.

### 2. **ANOVA**
- **Hypothesis**: Is there a significant difference in the average age of passengers across different classes (First, Second, and Third)?
- **Result**: The p-value is significantly less than 0.05, so we reject the null hypothesis, indicating a significant difference between the classes.

### 3. **Wilcoxon Signed-Rank Test**
- **Hypothesis**: Is there a significant difference between two related age measurements (before and after a simulated event)?
- **Result**: The p-value is less than 0.05, indicating a significant difference between the paired samples.

## Files
- `t_test.ipynb`: Jupyter notebook performing the t-test on male vs. female passengers' ages.
- `ANOVA.ipynb`: Jupyter notebook performing ANOVA on the average age across passenger classes.
- `Wilcoxon_Signed_Rank.ipynb`: Jupyter notebook performing the Wilcoxon Signed-Rank test on paired age samples.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/hypothesis-testing-project.git
    ```
2. Install required libraries:
    ```bash
    pip install seaborn scipy pandas matplotlib
    ```
3. Open any Jupyter notebook (e.g., `t_test.ipynb`) and run the cells.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: `seaborn`, `scipy`, `pandas`, `matplotlib`

## Conclusion
This project showcases the use of hypothesis testing to identify significant differences in datasets. The results provide insights into patterns that would otherwise remain hidden, demonstrating the power of statistical analysis.
