# dsnd-c2

**Project Motivation**

For this project I selected the DataBank from the World Bank Group, as one of the most frequently used source for World Development Indicator data by many researchers and policymakers. I'd like to use this analysis to understand:
- What are the key factors for Total Factor Productivity?
- Does the size of economy matters to what are the key factors?
- Is there a "Silver Bullet" for GDP growth (Balanced vs. Targeted approach)?

**Libraries Used**

For tooling I used the commonly used Python libraries like pandas, numpy, matplotlib and sklearn.

**Documents**

In the Main.ipynb you'll find the Python code in a Juputer Notebook with the steps for my exploratory data analysis (EDA) and the modeling.

**Summary**

While the DataBank provides 1,500+ features (Series) across 11 categories, I started my analysis with 31 features covering these 5 categoies:
* Education
* Health
* Infrastucture
* Trade
* Labor
I used GDP in today's USD amount as the target to showcase what indicator has the strongest correlation with GDP attempted to build a model around that.

Through the analysis, Tourism and Infrastructure (especially broadband, telephone and cellular connection) has a significant correlation with difference in GDP.

Link to my blog post: https://mshi-so.github.io/dsnd-course2/

**Acknowledgement**

The data used in this analysis in located on DataBank by World Bank Group, link here: https://databank.worldbank.org/source/world-development-indicators#