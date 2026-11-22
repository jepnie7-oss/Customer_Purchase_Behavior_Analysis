# Customer_Purchase_Behavior_Analysis
Statistical analysis of customer purchasing behavior across multiple sales channels using Python, Mixed-effects Models and GEe 
# Customer Purchase Behavior Analysis

## Project Overview

This project investigates customer purchasing behaviour across three sales channels: Mobile App, Website and Social Commerce. The objective was to determine whether customer order values differ significantly across these channels while accounting for repeated purchases by individual customers.

The analysis applies statistical methods to transform raw transaction data into meaningful business insights.

## Objectives

- Examine customer purchasing patterns across sales channels.
- Compare order values across Mobile App, Website and Social Commerce.
- Investigate whether observed differences are statistically significant.
- Account for repeated transactions from the same customers.
- Develop evidence-based business recommendations.

## Dataset Overview

The project used an Excel workbook containing two datasets:

- Orders: Transaction-level information.
- Customers: Customer-level information.

After data cleaning, the analysis retained:

- 650 valid orders.
- 180 customers.
- 3 sales channels.

## Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib

## Statistical Methods

The analysis included:

- Descriptive statistics
- One-way ANOVA
- Levene's test
- Shapiro–Wilk test
- Kruskal–Wallis test
- Friedman test
- Linear mixed-effects modelling
- Generalized Estimating Equations (GEE)
- Model diagnostics and comparison

## Key Findings

Order Distribution

- Mobile App: 254 orders (39.1%)
- Website: 233 orders (35.8%)
- Social Commerce: 163 orders (25.1%)

Average Order Value

- Mobile App: KSh 4,427.66
- Website: KSh 4,107.15
- Social Commerce: KSh 4,288.40

## Statistical Findings

The analysis found no statistically significant evidence of differences in order value across the three channels.

The preferred mixed-effects model and GEE analysis both supported this conclusion. The overall GEE channel test returned a p-value of 0.185.

This does not establish that the channels are equivalent; it means the analysis did not detect a statistically significant difference.

## Business Recommendations

- Avoid selecting a winning channel using average order value alone.
- Evaluate profitability after operational and marketing costs.
- Monitor repeat purchases and customer retention.
- Examine customer acquisition costs and lifetime value.
- Investigate cross-channel customer journeys.

## Project Conclusion

This project demonstrates the application of statistical analysis and clustered modelling to a practical business problem.

The findings highlight the importance of using appropriate statistical methods before making business decisions based on observed differences in transaction data.

## Limitations

- The analysis focused primarily on order value.
- Product costs and marketing expenses were not included in the main comparison.
- The matched-customer analysis covered 62 customers with observations in all three channels.
- The findings are observational and do not establish causation.

## Author

Name:Winnie Jepleting 
Field: Applied Statistics with Computing
Area of Interest: Data Analytics, Statistical Modelling and Business Intelligence
