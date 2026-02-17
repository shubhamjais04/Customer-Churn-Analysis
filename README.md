# Telco Customer Churn Analysis

My second data analysis project where I analyzed a telecom company's customer 
data to understand why customers leave (churn).

## What is Churn?

Churn means when a customer stops using a service and leaves for a competitor.
This is a real business problem every company faces!

## Dataset

- 7,043 customers
- 21 columns (demographics, services, account info)
- Source: IBM Watson / Kaggle

## Questions I Answered

1. What is the overall churn rate?
2. Does gender affect churn?
3. Do senior citizens churn more?
4. Does contract type matter?
5. Which internet service has most churn?
6. Do new customers churn more?
7. Does monthly charge affect churn?
8. Which payment method has most churn?

## Key Findings

1. **26.5% of customers churned** - 1 in 4 customers leaving
2. **Contract type is biggest factor** - monthly contracts have 43% churn vs 3% for 2-year
3. **New customers churn most** - first year is most critical
4. **Fiber optic users churn more** - 42% churn rate
5. **Senior citizens churn more** - almost 2x higher than non-seniors
6. **Gender doesn't matter** - males and females churn equally

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Files

- `churn_analysis.ipynb` - main analysis notebook
- `data/` - dataset
- `images/` - saved visualizations

## How to Run
```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook churn_analysis.ipynb
```

## What I Learned

- Fixing data type issues (TotalCharges was stored as text)
- Analyzing categorical data with groupby
- Finding business insights from data
- Real datasets need more cleaning than tutorial datasets!

---

**Second project in my data science journey!**

Shubham Jaiswal
- GitHub: [@shubhamjais04](https://github.com/shubhamjais04)

- LinkedIn: [linkedin.com/in/shubhamjaiswal2004](https://linkedin.com/in/shubhamjaiswal2004)


