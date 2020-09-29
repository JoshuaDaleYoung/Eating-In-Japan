Analyzing a dataset to find the best price point and types of restaurants in Japan. 
I have lived in six different countries and hopefully next on that list is Japan. My first takeaway from  analyzing the dataset is, wow I need to really be saving that tech money if I am going to have a quality visit.
The analysis starts standard by importing libraries and taking an initial look at the data. For a brief overview I look at how the variables correlate and create a boxplot of restaurants overall ratings with their price point. 
It is obvious to see that the more you spend the better rating the restaurant receives.
To hone in on this I look specifically at the lunch and dinner ratings with their price point. In order for me to better understand the data I change the variables into USD.
Dinner does the expected where the more you spend the overall better quality you can anticipate. Lunch on the other hand drops off in quality after spending more than $85. This is my first insight. 
To better compare the dining experience of lunch and dinners I create the variables 'Cost_Rating_Lunch' and 'Cost_Rating_Dinner. This was done by dividing the average meal price with its corresponding rating.
I used these new variables to see which restaurants had the best and worst ratings. To better visualize this process I extracted the dataset with pandas and processed the graphs in Tableau.
Ryokan restaurants were the clear winner while European Style Curry restaurants were the clear looser. 
