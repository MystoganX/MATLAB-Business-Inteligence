# Matlab - Data Analysis & Visualization
*The examples shown in this section use the data from Tableau's fictional store [Superstore (Sample - Superstore.xls)](https://community.tableau.com/s/question/0D54T00000CWeX8SAL/sample-superstore-sales-excelxls) and [Twitter's Customer Support (twcs.csv)](https://www.kaggle.com/thoughtvector/customer-support-on-twitter). The Superstore file is a spreadsheet with records of sales data from 2014 to 2017, while twcs.csv contains logs of the messages from the customer support chat.*

This section explores different techniques to read and visualize data for business purposes. This includes typical analysis of a retail store sales, in order to determine how is business going on and how different type of customer behave, and chat logs to determine global engament and busy hours.

This goes from **reading** the files, **plotting daily sales** data:

Raw data |  Processed yearly data
:-------------------------:|:-------------------------:
<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/FilteredSales_small.png" width="800" height="600" />  |  <img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/YearlySales_small.png" width="800" height="600" />


To answering more complex questions with different visualization techniques, like:

**How profitable are the company's offers, in terms of each customer's behaviour?**

<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/CustomerSalesVsProfit_small.png" width="800" height="600" />

Or cheking **performance metrics**, like the *average ticket* of the items sold by the store:

Customer Sales vs Quantity |  Average Ticket 
:-------------------------:|:-------------------------:
<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/CustomerSalesVsQuantity_small.png" width="650" height="400" />  |  <img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/AverageTicket_small.png" width="650" height="400" />

Or how is the company's *margin of profit* evolving over the years 

<img src="https://github.com/MystoganX/MATLAB-Data-Analysis/blob/master/Figures/ProfitVsCost.png" width="500" height="300"/>
