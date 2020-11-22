# Matlab - Data Analysis & Visualization
*The examples shown in this section use the data from Tableau's fictional store [Superstore (Sample - Superstore.xls)](https://community.tableau.com/s/question/0D54T00000CWeX8SAL/sample-superstore-sales-excelxls) and [Twitter's Customer Support (twcs.csv)](https://www.kaggle.com/thoughtvector/customer-support-on-twitter). The Superstore file is a spreadsheet with records of sales data from 2014 to 2017, while twcs.csv contains logs of the messages from the customer support chat.*

This section explores different techniques to read and visualize data for business purposes. This includes typical analysis of a retail store sales, in order to determine how is business going on and how different type of customer behave, and chat logs to determine global engament and busy hours.

This goes from simple **reading** and **processing** of the data to plot typical sales graphs:

Raw data |  Processed yearly data
:-------------------------:|:-------------------------:
<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/FilteredSales_small.png" width="800" height="600" />  |  <img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/YearlySales_small.png" width="800" height="600" />

To checking **performance metrics** and answering more complex questions, like:

1) How profitable are the company's offers, in terms of each customer's behaviour?

<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/CustomerSalesVsProfit_small.png" width="800" height="600" />

2) Which is the the *average ticket* of the items sold by the store? Does it represent well our customer's behaviour?

Customer Sales vs Quantity |  Average Ticket 
:-------------------------:|:-------------------------:
<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/CustomerSalesVsQuantity_small.png" width="650" height="400" />  |  <img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/AverageTicket_small.png" width="650" height="400" />

3) How is the company's *margin of profit* evolving over the years?

<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/ProfitVsCost_small.png" width="500" height="300"/>

4) Which are the busiest hours for our company? In a week, is there an specificly busy time where resources should be allocated?

Original | Clustered
:-------------------------:|:-------------------------:
<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/WeeklyGlobalEngagement_small.png" width="800" height="600" />  |  <img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/WeeklyGlobalEngagementCluster_small.png" width="800" height="600" />

5) Is the workload distribuited homogeneously over the month? Or clients preffer specific days to interact with the company?

<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/MonthlyGlobalEngagement.png" width="800" height="600"/>
