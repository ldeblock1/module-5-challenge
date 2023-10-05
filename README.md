# module-5-challenge
In this challenge I merged two data frames containing mouse data and the study results for a clinical study testing the efficacy of certain cancer treatments in shringing tumor sizes in mice. 

Then, I name sure all data was grouped by mouse_ID and Timepoint to find duplicates and so I can anayze the the data by timepoint.

I first checked for all duplicate data and displayed them to see what they were. Then I dropped them to clean the dataset and ensure consistent results. 

Then, I created summary statistics for tumor valumes per drug. I did this twice in two methods showing my pthon knowledge.

Next, I used a bar chart plot to show the number of mice and timepoints there were for every drug. This shows that some trials may have taken longer or used more mice than others. 

Next, I plotted a pie chart to show the distribution of male to female mice used in these trials. The results showed that there were slightly more male mice than female mice used but it's fairly even overall. I plotted twice using matplot's functions and panda's functions.

Next, I narrowed the data to four drugs, 'Capomulin', 'Ramicane', 'Infubinol', 'Ceftamin' to show differences in the final tumor sizes among mice using these drugs. Then, I calculated the interquartile ranges for these results to find outliers. 

Next, I plotted a box and whisker plot to visualize these interquartile ranges and outliers (there was only one)

Next, I plotted a line graph to show the decline in tumor volume of one mouse taking Capomulin. The shrinkage was significant and fairly impressive. 

Next, I used a scatterplot to show the correlation of mice weight vs average tumor volume for mice taking Capomulin. The graph seems to show a fairly strong positive correlation.

Finally, I used the lineregress() function to do linear regression on the scatterplot data and plotted a line using the slope and intercept values calculated from the linregress() function. The program also displays the r-value (correlation coefficient) of 0.84 confirming a very strong positive relationship. The slope of 0.95 shows that on average for every 1(g) increase in mouse weight there is a 0.95 mm^3 increase in tumor volume with a baseline volume of 21.55 mm^3. 
