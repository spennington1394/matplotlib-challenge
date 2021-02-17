Pharmaceutical analysis with visualizations using python library matplotlib.

Dataset: anti-cancer pharmaceutical data that observed 249 mice identified as having squamous cell carcinoma. The data observes the mice over a 45 day period, measuring tumor size of mice given treatments of Campomulin vs other treatment regimens.

Step 1: 

Set dependencies (matplotlib.pyplot,pandas, numpy, scipy.stats, and scipy.stats) and read in csv files. 

Step 2: 

Merged study and mouse data together. Then groupby drug type to generate a statistic dashboard that contains: mean, median, variance, standard deviation, standard error mean (SEM) of tumor size.
 
Step 3:

Generated a bar plot that displayes the number of total mice for each treatment regimen throughout the 45 day observation period. 

Step 4: 

Generated a pie plot that shows the distribution of female to male mice. 

Step 5:

Calculated the final tumor volume of each mouse across the observed four most treatment regims: Capomulin, Ramicane, Infubinol, and Ceftamin. 

Then calculated the quartiles and inter quartile range to observe any potential outliers across the treatment regimens. 

Generated a box and whisker plot of the final tumor volumne for four afermentioned treatment regimens and highlighted outliers.

Step 6:

Selected a singular mouse that was treated with Capomulin and generated a line plot of tumor volumne vs. time point for that mouse.

Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volumne for the Capolumlin treatment. 

Step 7:

Generated a document that highlights three observations made from visualizations and calculations.
