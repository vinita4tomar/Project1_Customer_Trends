# Project1_Customer_Trends
This repository contains files used for analysis of customer data sets to understand consumer behavior patterns.

shopping_trends_data.csv is the dataset

customer_trends_code.ipynb contains code used for massaging and analyzing data. Creating visual graphs to figure out different trends.

*.ppt is the presentation given by group with the key findings of the analysis
#Data analysis 
Seasonal Data: 
  Is there variation in purchasing patterns with seasons? 
    Chi-Square Test of Independence to see if there is statistical significance in the variation of Season and Color as well as Season and Item             Purchased
    Designed for Categorical Data like “Season” and “Color” 
      Results: 
      Degrees of Freedom: 12, alpha=0.05
      Critical Value: 21.026
      Chi Squared Statistic = 0.473
      Drawn Conclusions: 
      Chi Squared value of 0.473 is less than critical value 21.026
      Fail to reject null hypothesis
      Suggests there is not enough evidence to conclude a significant association between color and season based on the corrected data

  Designed for Categorical Data like “Season” and “Item Purchased” 
      Results: 
      Degrees of Freedom: 12, alpha=0.05
      Critical Value: 16.916
      Chi-Square Statistic: 24.42
      Drawn Conclusions: 
      24.42 > 16.916
      Can reject null hypothesis
      Suggests there is enough evidence to conclude a significant association between item purchased and season based on the corrected data 
      

Gender:  
  How do purchases breakdown by gender through summary statistics? 
    After displaying the data via different visualizations, we were able to discover that 

Age: 
  What are the most popular categories among different age groups?
     Clothing is the most popular category across all age groups.
     The 18-25 age group shows a strong preference for clothing, making the most significant contribution to purchases in this category.
     Accessories are the second most popular category, with the 41 - 65 age group leading the purchases, indicating interest in accessories among            this demographic.
     The 66-70 age group spends the least across all categories.
     The 18 - 25 and 26 - 40 age groups show more similar spending patterns.
     There is a significant drop in purchase amounts in the outerwear category for all age groups when compared to other categories.




