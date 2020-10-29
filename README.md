# Data-Visulaization-on-Habermans-Dataset
This is cancer patients Dataset Who had undergone breast cancer surgery between the years 1958 and 1970.on the basis of patients who had survived less than 5 year &amp; more than 5 years after lymph node surgery. on the survival of patients here we used various data Visualization Techniques like Pair Plots Univariate analysis  Violin plots Scatter plots and other
1-There are 4 attribute out of which status is the output feature.
2-This dataset is unbalanced dataset out of 306 oprationsperformed
a)225 cancer patients have survival status1 who had survived more than 5 years.
Medians: 0.0 0.0 4.0  
Quantiles: [0. 0. 0. 3.] [ 0.  1.  4. 11.]  
90th Percentile: 8.0 20.0  
Median Absolute Deviation 0.0 5.930408874022408 
b)81 cancer patients who had survival status 2 who has short survived i.e less than 5 years.
3- Age of the patients vary from 30-83 with average age of 52. Maximum number of positive lymph nodes observed is 52,nearly 75% have 4 positive lymph nodes and 25% have 0 positive lymph nodes.
4-Bivariate analysis with scatter plot a)We observed that blue datapoints overlaps with orange datapoints so we cant make any conclusion from 2D scatter plot.so we tried Bivariate analysis using 3D scatter plot here also its hard to conclude because of overlapping nature of all plots.
5-Univariate analysis by using HISTOGRAM,CDF,PDF.
a)From the PDF plot of patients age & operation year we observed that no any linearly seaparable nature of any plot most cases data points aresame for both status so we cant make any concluison from both of them.Axilary lymph node shows somewhat useful plot that we can see some difference n distribution.patients with 0-3 nodes have better probability of survival.
b)From CDF plot we can conclude that as the no of axialry lymph nodes increses patients survival chances also decreases.
6- From stastical data the mean of status 2 is greater than mean of status1.Thus haberman data will be helpful to diagnose cancer by using above different python progrmming
