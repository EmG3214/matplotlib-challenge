# matplotlib-challenge
This process digs onto pharmaceutical data testing on rats.
We begin by perparing the data, then genrating summary statistics in two ways.

Then we create pie and bar charts in wo ways to assess the distribution of mouse sex in the study.
    The bar chats sumply shows the number of data points for each drug regimen.
    The pie chart shows ther is roughly an equal distibution of male and female rats.

We then calculate quartiles and find outliers by defining and calling a function that includes a for loop
    The outliers show only one outlier for the Infubinol max tumor volume data points.
    The boxplot shows this one outliner, and also shows that the lowest overall final tumor volume was for the Drug Regimen Ramicane, 
    but Capomulin had a similar mean with slightly smaller variance.Both infubinol and Ceftamin had much higher final tumor volumes and
    larger variances than the other two regimens. 

We then create a line plot for a single mouse treated with Capomulin.
    This mouse's tumor volume overall decreased with the treatment.

We then create a scatter plot of mouse weight and average tumor volume.
Finally, we create correlation and regression plot. 
    The final correlation of mouse weight and tumor volume is 0.84, with an r-squared of 0.71
    This means that there is a probable relationship between mouse weight and tumor volume.
