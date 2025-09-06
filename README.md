![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualizations-orange.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

# Amazon Clothing Sales EDA Project

## Project Overview
Exploratory Data Analysis of Amazon clothing sales data.  
This project uncovers insights into pricing strategies, customer behavior, product returns, and sales trends.  
It uses **Python, pandas, seaborn, matplotlib, scipy, and scikit-learn** to perform statistical testing, advanced analysis, and machine learning predictions.  

## Features
- Data cleaning, transformation, and feature engineering
- Univariate and multivariate analysis
- Hypothesis testing with statistical methods
- Cohort analysis for customer retention
- RFM segmentation for customer insights
- Logistic regression model for return prediction
- Cleaned dataset export for further analysis

## Example Visualizations
- Price distribution histogram  
- Monthly revenue trend line chart  
- Return rate heatmap by category and region  
- RFM segmentation scatter plot

## Methodology
1. **Data Loading & Cleaning**  
   - Data imported directly from Google Sheets.  
   - Removed duplicates and handled missing values.  
   - Feature engineering: discounts, unit price, delivery flags, temporal features.

2. **Univariate Analysis**  
   - Distribution of price, categories, and return rates.  
   - Identified most common product categories and typical pricing patterns.

3. **Bivariate & Multivariate Analysis**  
   - Relationship between discounts and quantities.  
   - Impact of delivery days on customer ratings.  
   - Regional and device-based behavioral differences.  
   - Monthly revenue trends.

4. **Hypothesis Testing**  
   - Tested assumptions using correlation, ANOVA, Chi-square, and T-tests.  
   - Key hypotheses included: impact of discounts on sales, effect of delivery time on ratings, and device/region-based differences.

5. **Advanced Analyses**  
   - **Cohort Analysis** for retention tracking.  
   - **RFM Segmentation** to group customers based on recency, frequency, and monetary value.  
   - **Price Elasticity** analysis to study sensitivity of demand to price changes.  
   - **Return Prediction** using logistic regression to identify factors influencing product returns.

6. **Visualization Expectations**  
   - Revenue time series trends.  
   - Boxplots for price distributions.  
   - Heatmaps for category-region return rates.  
   - Scatter plots for discounts vs. quantity and delivery days vs. rating.  
   - Bar charts of top brands.

## Key Findings
- **Discounts** positively correlated with higher quantities sold.  
- **Delivery speed** impacts customer satisfaction; longer deliveries lead to lower ratings.  
- **Returns** varied significantly across regions and categories.  
- **Device usage** (mobile vs desktop) influenced average spending patterns.  
- Logistic regression model highlighted **delivery days** and **discount percent** as strong predictors for returns.

## Setup & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/amazon-clothing-eda.git
   cd amazon-clothing-eda
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the `Eda Project Template.ipynb` notebook in your browser.  
5. Replace the `sheet_id` and `gid` in the config section with your own Google Sheet details if needed.  
6. Run all cells in sequence.  
7. Cleaned dataset will be exported as `amazon_clothing_sales_cleaned.csv` in the project folder.

## Project Structure
```
├── Eda Project Template.ipynb   
├── amazon_clothing_sales_cleaned.csv 
├── requirements.txt           
├── README.md                   
```

## License
This project is licensed under the MIT License.  
Feel free to use and modify with attribution.
