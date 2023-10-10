In this challenge I used Pandas and MatplotLib to analyze the a study of 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

First, I prepared the data by merging the mouse_metadata and the study_results DataFrames info a single DataFrame.    

I generated summary statistics (mean, median, variance, standard deviation, and SEM of the tumor volume) for each Drug Regimen and displayed the results in a table.

I created bar charts and pie charts using Pandas and Matplotlib.

I calculated quartiles, found outliers, and created a box plot for the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
    
I generated a line plot of tumor volume versus time point for a single mouse that was treated with Capomulin. I generated a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

Lastly, I calculated the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen. 

Findings:
-There seemed to be a strong correlation between mouse weight and the average tumor volume. As the mouse weight increased the averge tumor volume increased. 
-The line plot of tumor volume vs. time point for a single mouse treated with Capomulin shows improvement over 35 days time for the mouse l509, however there is an increase in the data at the end of the graph which I would want to investigate more and understand why the average tumor volume is increasing between 35-40 days and then the data stops.
-For the box plot that shows the distrubution of the tumor volume for each treatment group (Capomulin, Ramicane, Infubinol, and Ceftamin), it clearly shows that Capomulin, Ramicane had the best results with the average final tumor volume (mm3) being about 38 mm3 and 35 mm3 respectively, whereas for Infubinol, and Ceftamin they were closer to 60 mm3.
