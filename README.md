Market Profitability Analysis: France vs Europe

This project analyzes financial performance across multiple countries with a special focus on France and its comparison to the European region. Using a business dataset sourced from Kaggle, we explore which factors most influence profitability and how different countries vary in performance metrics like Sales, Profit, Discounts, and Units Sold.

Objective

- Identify which features most impact Profit.
- Compare patterns between France and the broader Europe.
- Provide insights for strategic decision-making based on data.

Dataset

- Source: Kaggle – Company Financial Data
- Content: Sales, Profit, Discounts, Product Type, Segment, Country, Date, COGS, Manufacturing Price, and Sale Price

Methods

- Data Cleaning: Removed currency symbols, handled negative values in parentheses, and removed missing data.
- Exploratory Data Analysis:
  - Grouped bar charts of Sales and Profit by Country
  - Correlation analysis within France and Europe
  - Heatmaps for comparison
- Feature Encoding: Converted categorical columns (e.g. Segment) into numerical form for correlation calculations.

Key Findings

- France had one of the highest profits, despite not having the highest sales.
- The strongest predictors of profit were Sales, Gross Sales, COGS, and Sale Price.
- Units Sold had weak correlation with profit, indicating that value matters more than volume.
- Segment type showed negative correlation with profit, suggesting some customer types were less profitable.

Project Structure

project_notebook.ipynb       – Full analysis in Jupyter / Google Colab  
presentation.pptx            – PowerPoint report summary  
plots/                       – Exported visualizations  
README.md                    – Project description and overview

Tools Used

- Python (Pandas, NumPy, Seaborn, Plotly)
- Jupyter Notebook / Google Colab
- PowerPoint
- GitHub for version control

Conclusion

The analysis shows that increasing the total value of sales, rather than focusing on volume alone, is key to maximizing profit. France's profitability suggests that efficient pricing strategies and segment targeting are important drivers of financial success.
