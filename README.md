# dsnd-c2

**Data Source**
For this project I selected the DataBank from the World Bank Gorup, as one of the most frequently used source for World Development Indicator data by many reseaarchers and policymakers.

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