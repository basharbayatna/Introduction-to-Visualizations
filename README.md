# Cumulative Interest Analysis for a $400,000 Loan

This notebook analyzes how cumulative interest grows over time for a $400,000 loan at two different annual interest rates: **3%** and **5%**.  

## Dataset
The dataset contains monthly cumulative interest for each interest rate over the term of the loan.  [cumulative_interest - cumulative_interest (2).csv](https://github.com/user-attachments/files/21969260/cumulative_interest.-.cumulative_interest.2.csv)

**Example data points:**

| Month | 3% Cumulative Interest | 5% Cumulative Interest |
|-------|-----------------------|-----------------------|
| 1     | 1000.00               | 1666.66               |
| 2     | 1998.28               | 3331.32               |
| …     | …                     | …                     |
| 359   | 207,106.01            | 373,017.23            |
| 360   | 207,106.01            | 373,017.23            |



## Steps Performed
1. Loaded the dataset using `pandas`.  
2. Selected and explored relevant columns: `Month`, `3% Cumulative Interest`, `5% Cumulative Interest`.  
3. Plotted cumulative interest over time using `matplotlib`.  

## Key Insights
- Cumulative interest increases over time due to compounding.  
- **3% interest** grows steadily over the loan period.  
- **5% interest** grows much faster, showing the impact of higher interest rates.  
- For a $400,000 loan, the total cumulative interest after 360 months reaches **$207,106.01** at 3% and **$373,017.23** at 5%. 

### Figure: Cumulative Interest Over Time

<img width="597" height="455" alt="Cumulative Intrest Over 30 Years" src="https://github.com/user-attachments/assets/961a165c-e967-4b41-8831-80a4d70ba27b" />



