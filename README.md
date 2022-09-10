# (Salary Dataset)
## by (Michael Afolami)


## Dataset

> The name of my dataset is Salaries Dataset, and it was obtained from Kaggle. THe dataset contains 148654 observations and 12 variables. As part of my wrangling steps, I dropped a column that contained zero values and had no contribution to the entire dataset. I identified missing numbers and did imputation with the mean. I then moved ahead with the analysis.


## Summary of Findings

> 'id' and 'year' columns have negative and insignificant correlation respectively with our target variable. Hence, for pairplot, I will be using only those columns with significant correlation values.
> TotalPay' , 'BasePay', and 'Benefits' appear to be positively correlated with 'TotalPayBenefits'
>  the number of job titles/employees supports the assumption that TotalPayBenefits increase by the year due to increase in the number of employees
> As the year rises, totalpaybenefits increases, and so does totalpay, thus maintaining a close relationship and a strong positive correlation. I would not have thought that years would have an effect on how much is paid as salary, but as I have opined, as long as there is no noticeable attrition and more employees are employed yearly, then salaries are meant to increase!

## Key Insights for Presentation

> My key insight for presentation is the effects that any pay an employeee gets apart from their base pay, definitely affects their overall pay.
Hence, I will check 
> TotalPayBenefits by year
> Top ten most common jobs
> Total Pay vs TotalPayBenefits
