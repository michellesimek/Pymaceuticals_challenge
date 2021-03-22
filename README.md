# Pymaceuticals_challenge

The purpose of this assignment was to analyze data from a recent animal study. The study took mice who were identified with having a SCC tumor growth and treated them with a variety of drug regimens. The drugs in the study were Capomulin, Ceftamin, Infubinol, Ketapril, Naftisol, Placebo, Propriva, Ramicane, Stelasyn, and Zoniferol.
 
## Analysis 
To begin the analysis, two datasets were merged - one dataset included mouse metadata and one dataset include the study results.After merging the two datasets, we cleaned the merged dataset to remove the mouse ID that had duplicated timepoint information. WIth the removed Mouse ID, the study now contained results for 248 mice.

#### Summary Statistics
Using the clean merged dataset, a table was created to get summary statistics for each drug regimen used in the study. Statistics included in the table were mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen. 

#### Measurement Data and Plots
* ##### Bar Plots
Bar plots were generated to show the total number of mice per drug regimen in the study. 

![GitHub Logo](/Graphs/total_count_per_drug.png)

* ##### Pie Plots
Pie plots were generated to show the distribution male and female mice in the study. 

![GitHub Logo](/Graphs/gender_distribution.png)

#### Top Drug Regimens
Looking at the data, there were four drug regimens that were most promising in the study: Capomulin, Ramicane, Infubinol, and Ceftamin.

A box and whisker plot of the tumor volumes for each top drug regimen was generated.

![GitHub Logo](/Graphs/most_promising.png)

#### Most Promising Drug Regimen: Capomulin
A line plot was generated to look at tumor volume versus timepoint of a mouse treated with the most promising drug regimen, Capomulin. I choose to look at mouse ID l509. Looking at the plot, you can see the volume size of the tumor greatly decreased with time as the mouse was treated with the drug.

![GitHub Logo](/Graphs/capomulin_line_plot.png)

#### Correlation and Regression 
Lastly, a scatter plot was generated looking at mouse weight versus average tumor volume for the drug Capomulin. Then the correlation coefficient and linear regression model was generated on top of the scatter plot.

![GitHub Logo](/Graphs/average_tvolume_vs_weight.png)

![GitHub Logo](/Graphs/correlation_regression.png)