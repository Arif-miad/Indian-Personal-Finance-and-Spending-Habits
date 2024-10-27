

# Personal Financial Management Dataset

## Overview

This dataset contains detailed financial and demographic data for **20,000 individuals**, focusing on income, expenses, and potential savings across various categories. The aim of this dataset is to provide insights into personal financial management and spending patterns.

## Dataset Description

The dataset includes the following key features:

### Income & Demographics

- **Income**: Monthly income in currency units.
- **Age**: Age of the individual.
- **Dependents**: Number of dependents supported by the individual.
- **Occupation**: Type of employment or job role.
- **City_Tier**: A categorical variable representing the living area tier (e.g., Tier 1, Tier 2).

### Monthly Expenses

The dataset records various monthly expenses in the following categories:

- **Rent**
- **Loan Repayment**
- **Insurance**
- **Groceries**
- **Transport**
- **Eating Out**
- **Entertainment**
- **Utilities**
- **Healthcare**
- **Education**
- **Miscellaneous**

### Financial Goals & Savings

- **Desired_Savings_Percentage**: The target percentage of monthly income that individuals aim to save.
- **Desired_Savings**: The target amount for monthly savings.
- **Disposable_Income**: Income remaining after all expenses are accounted for.

### Potential Savings

Includes estimates of potential savings across different spending areas:

- **Groceries**
- **Transport**
- **Eating Out**
- **Entertainment**
- **Utilities**
- **Healthcare**
- **Education**
- **Miscellaneous**

## Usage

This dataset can be utilized for various analyses, including but not limited to:

- Personal finance management studies
- Spending behavior analysis
- Savings potential estimation
- Demographic impact on financial habits

```python
plt.figure(figsize = (15, 35))
for i, col in enumerate(df.columns, 1):
    plt.subplot(7, 4, i)
    sns.histplot(x = df[col])
    plt.title(f"Histogram of {col} Data")
    plt.plot()

```


![Histplot](https://github.com/Arif-miad/Indian-Personal-Finance-and-Spending-Habits/blob/main/indian.png)



## License

This dataset is licensed under the MIT License. Feel free to use it for personal or research purposes.

## Contact

For questions or feedback, please contact:
<body>
<p align="center">
  <a href="mailto:arifmiahcse952@gmail.com"><img src="https://img.shields.io/badge/Email-arifmiah%40gmail.com-blue?style=flat-square&logo=gmail"></a>
  <a href="https://github.com/Arif-miad"><img src="https://img.shields.io/badge/GitHub-%40ArifMiah-lightgrey?style=flat-square&logo=github"></a>
  <a href="https://www.linkedin.com/in/arif-miah-8751bb217/"><img src="https://img.shields.io/badge/LinkedIn-Arif%20Miah-blue?style=flat-square&logo=linkedin"></a>

 
  
  <br>
  <img src="https://img.shields.io/badge/Phone-%2B8801998246254-green?style=flat-square&logo=whatsapp">
  
</p>




