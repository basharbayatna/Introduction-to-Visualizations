# Cumulative Interest Analysis for a $400,000 Loan

This notebook analyzes how cumulative interest grows over time for a $400,000 loan at two different annual interest rates: **3%** and **5%**.  

## Dataset
The dataset contains monthly cumulative interest for each interest rate over the term of the loan.  [cumulative_interest - cumulative_interest (2).csv](https://github.com/user-attachments/files/21969260/cumulative_interest.-.cumulative_interest.2.csv)


## Steps Performed
1. Loaded the dataset using `pandas`.  
2. Selected and explored relevant columns: `Month`, `3% Cumulative Interest`, `5% Cumulative Interest`.  
3. Plotted cumulative interest over time using `matplotlib`.  

## Key Insights
- Cumulative interest increases over time due to compounding.  
- **3% interest** grows steadily over the loan period.  
- **5% interest** grows much faster, showing the impact of higher interest rates.  
- The dataset reports cumulative totals, which explains why the first months already show substantial amounts.  

### Figure: Cumulative Interest Over Time

```python
import matplotlib.pyplot as plt

X = df['Month']
Y1 = df['3% Cumulative Interest']
Y2 = df['5% Cumulative Interest']

fig, ax = plt.subplots()
ax.plot(X, Y1 , label= '3% Cumulative Interest')
ax.plot(X, Y2, label = '5% Cumulative Interest')
ax.legend()
ax.set(ylabel = 'Interest Fees in $', xlabel= 'Months', title= 'Cumulative Interest Over Time for $400,000 Loan')
plt.show()
