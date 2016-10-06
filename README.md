# Project 6 -Data Visualization

##Summary
-This PRoject Charts Loans Across different Years and their performace.The data used is from Prosper.The chart answers one simple quiestion : When were there most defaults and did they correspond with the crisis in 2007.
##Design
###Data wrangling
-The dataset was mostly clean, so there was almost no need to wrangle it.For the purpose of my analysis,however, I did npt need the whole dataset and there were also some values in the wrong format. The fist thing I had to chage was the LoanOrigination, which was in the format of quarters of a year ,but for the purpose of my analysis, I needed it to be only in the Year format. The second Item I had to chage(or so I thought), was the LoanStatus.There I chaget to have only two values:performing and nonpoerfomring if the loan was chargedoff or Defaulted. After Some feedback, I also modified the original LoanStatus, to drop the current value, because it vas useless for the purpose of the analysis.

###Visualization
-For my visualization I used Dimple.js, because it was sufficient for this plot. At first, I thought about using linechart with bubbles to show the finding, but when I plotted the chart, It became clear that a simple stacked bar chart will be sufficient.
-After first feedback, I reverted back to the origninal LoanStatus, because for some, it was not clear what the preforming and nonperforming meant. Also, I modified the LoanStatus, to drop the Current value,because it showed the loans, that were still working an not likey to go bad, which was not useful for my analysis. And I also played with various scales of the y axis, but, in the end, the original showed the finding most clearly.

##Feedback
###Feedback1
-The First Feedback I received. Pointed out, that it is unclear what i meant with Performing vs Nonperforming, And that it was really hard to find the result,that I pointed out, in the visualization.
###Feedback2
-In The second feedback I received, I was told, That it was still hard to find my results in the visualization, that I can not judge the data, if I dont know how the Current loans will work out.
###Feedback3
-The third feedback was the most Straight forward I received. I was told that this visualization shows the finding clearly, but that the finding is not really interesting and thus the visualization is not really useful.
##Resources
www.udacity.com
http://bl.ocks.org/mbostock/1134768
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart
http://bl.ocks.org/mbostock/b2fee5dae98555cf78c9e4c5074b87c3

