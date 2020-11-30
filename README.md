# Matlab - Business Inteligence

This section explores different techniques to read and visualize data for business purposes. This includes typical analysis of sales data from a retail store, in order to determine *how is business going on?* and *how different type of customer behave?*, and also analysis of chat logs to determine global engagement and rush hours. 

Source data
---
- [Superstore.xls](https://community.tableau.com/s/question/0D54T00000CWeX8SAL/sample-superstore-sales-excelxls): records of sales data from Tableu's fictional store between 2014 and 2017. 
- [twcs.csv](https://www.kaggle.com/thoughtvector/customer-support-on-twitter): message logs from Twitter's Customer Support chat.

With this, we can check the company's **performance metrics** and answer questions like:

Scatter Plots
---

1) How profitable are the company's offers, in terms of each customer's behaviour?

<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/CustomerSalesVsProfit_small.png" width="800" height="600" />

2) Which is the the *average ticket* of the items sold by the store? Does it represent well our customer's behaviour?

Customer Sales vs Quantity |  Average Ticket 
:-------------------------:|:-------------------------:
<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/CustomerSalesVsQuantity_small.png" width="650" height="400" />  |  <img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/AverageTicket_small.png" width="650" height="400" />

Bar Plots
---

3) How is the company's *margin of profit* evolving over the years?

<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/ProfitVsCost_small.png" width="500" height="300"/>

Heatmap Charts
----

4) Which are the busiest hours for our company? In a week, is there an specificly busy time where resources should be allocated?

Original | Clustered
:-------------------------:|:-------------------------:
<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/WeeklyGlobalEngagement_small.png" width="800" height="400" />  |  <img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/WeeklyGlobalEngagementCluster_small.png" width="800" height="400" />

5) Is the workload distribuited homogeneously over the month? Or clients preffer specific days to interact with the company?

<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/MonthlyGlobalEngagement.png" width="800" height="600"/>
