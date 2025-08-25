# Cumulative Interest Visualization

This project demonstrates the growth of cumulative interest over time using a simple dataset and Python visualization.

## Dataset

The dataset contains monthly cumulative interest for two interest rates (3% and 5%). Columns include:

- `Month`: Month number (1–360 for 30 years)  
- `3% Cumulative Interest`: Total interest accumulated at 3%  
- `5% Cumulative Interest`: Total interest accumulated at 5%  

Original dataset path: `/content/drive/MyDrive/AXSOSACADEMY/01-Fundamentals/Week03/Data/cumulative_interest - cumulative_interest.csv`

## What I Did

1. **Loaded the Data**  
   - Read the CSV file into a Pandas DataFrame and displayed the first few rows.

2. **Plotted the Cumulative Interest**  
   - Used Matplotlib to plot `Month` on the x-axis and cumulative interest on the y-axis.  
   - Plotted both 3% and 5% cumulative interest on the same graph.  
   - Added labels, legend, and title for clarity.

## Key Insights

- Interest accumulates significantly over time. After 30 years:
  - **3% interest** grows to around **$12,000** from $1,000.  
  - **5% interest** grows to around **$50,000** from $1,000.  
- The difference between 3% and 5% rates increases over time, highlighting the power of compounding.  
- Small differences in interest rates can lead to large differences in returns over long periods.

## Figures

**Cumulative Interest Over 30 Years**

![Cumulative Interest Graph](figures/cumulative_interest.png)  
*Shows growth of cumulative interest for 3% and 5% interest rates over 30 years.*

**Monthly Interest Growth**

- 3% rate: increases gradually month by month.  
- 5% rate: faster growth, especially in later months due to compounding.

## Tools Used

- Python 3  
- Pandas  
- Matplotlib

## Author

- Bashar Bayatna
