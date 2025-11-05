# python-final-cafes-Rebekah-Ryan
Analyzing cafe sales for my Python final project

This is the orginal data set I was thinking of working with:
https://www.kaggle.com/datasets![Uploading download.png…]()
/wardabilal/exploring-coffee-sales-with-eda-and-visualization

I looked in the original data set a little more and have found there was no way to tell the difference between the rows, so I have swapped my data set to:
https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales
As this data set has more information, it tells the difference between transactions.

Data Manipulation: 
  Explain how and why these manipulations were necessary:
    For data manipulation, I need to, so there were quite a few I did, so I'm only going to go over a few for quite a few I grouped one column like days of the week or store location, and then got the average or sum of another column, for exsaple, unit price or total sales this is a good way to show it makes it more read able and is nice to see like what store sold the most of what product. Then, some of the other manipulations I did were making new columns. I made quite a few new columns. One I made was sales, where it multiplied the transaction quantity and the unit price, and that made the total for that sale. Lastly, I made some new sub-data frames for each location. This made it so I could look at data for each store and get more accurate data for, for example, seeing which store made the most over the half year.

Data Visualization:

I was unable to add the plotly graphs, but they are in the program.
<img width="984" height="584" alt="image" src="https://github.com/user-attachments/assets/f1bca111-b683-4c5b-9645-339985f809c8" />
<img width="1112" height="583" alt="image" src="https://github.com/user-attachments/assets/eff53c5f-6221-4518-b096-aacf021ca410" />


Statistical Analysis:


The purpose of this correlation test was to see if there were any correlations between any of the chosen rows of data.
With transaction date, there is little to no correlation with transaction quantity, unit price, and total sales, and a strong correlation with what month it was sold in. For transaction quantity, there is little to no correlation with month and sales, and a little negative correlation with unit price. The correlations for unit price show little to no negative relation with month and a strong correlation with total sales. And finally, there is little to no correlation between months and total sales.






