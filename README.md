# Plots using Python Matplotlib

**Dataset**

Pymaceuticals Inc. is a burgeoning pharmaceutical company based out of San Diego and specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

Data has been provided for an animal study in which 250 mice were identified with SCC tumor growth and were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.


**Objective**

 Generate all of the tables and figures needed for the technical report of the study and summarize the study results
 
 
**Analysis**
 
 The following tables/ figures were created:
 
* A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
* Bar plot that shows the number of data points for each treatment regimen.
* Pie plot that shows the distribution of female or male mice in the study.
* Final tumor volume of each mouse was calculated across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Quartiles and IQR were also calculated to quantitatively determine if there were any potential outliers across all four treatment regimens.
* Box and whisker plot of the final tumor volume for all four treatment regimens. Any potential outliers in the plot were highlighted.
* Line plot of time point versus tumor volume for a single mouse treated with Capomulin.
* Scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
Correlation coefficient and linear regression model was also calculated and plotted.
 
 
**Observations**
* There ia positive correlation (r = 0.84) between mouse weight and tumor volume.
* There are no outliers for the given data for drug regimen except Infubinol which has one outlier.
* For Capomulin regimen, 21 out 25 mice were alive at the end of study. For Ramicane, 20 out of 25 mice were alive. For other drugs, mouse deaths were high during the study.
* Gender of mouse had no effect on the effectiveness of drug.
