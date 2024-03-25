# Atliq_Excel_Project

Atliq is a company they sales hardware like pc,mouse,printer and so on to differnt custmoers like physical stores which is also known as brick and morters or online stores which are known as E-Commerce platform like Flipkart,amazon and then they sell the things to consumer like you and me.So for Atliq the customer is the stores like flikart,amazon etc and the consumer is the person who is cosuming the product.
Now those are retailer but Atliq has their own store Atliq e-store and Atliqu exclusive.
Now Atlique Hardware in infested with Excel Files.Now this company wants to get rid of these excel files and want to get a better understanding of their business by analyzing the data.
So here I have created a report on Sales Analytics and Finance Analytics for Atliq Company.

The first Report is Customer Performance Report and where I have shown the Net Sales for individual customer for 2019, 2020 and 2021.
And then I have compared the performance of last two year.

And then the next one is a Market Performance Report. Market means country here.
So here I found Net sales by countries for individual years.
We will also see the target for 2021 and then we will compare  what is the difference between the Actual net sales and Target.

To create both the reports I have used advance Excel here.I have performed ETL approach here.
So Here I have imported Atlique Sales CSV data into Excel.
And this Action is called Extract.
Then I have used Power Query for data transformation.That portion is called Transform.
And then the Transformed data  loaded back into Excel File.Which is called Load.

I have added the tables which are required for further analysis to the data model and then clicking on Diagram view I have created relationship between the tables using star schema putting the fact table at the center of all the Dimension tables.

I have created a complete Date table taking the data available in the fact_sales_monthly file and then using the calender date I have calculated the respective Fiscal year and month with the help of measures.

By using DAX(Data Analysis Expression) I have calculated Net Sales for individual customer for 2019, 2020 and 2021.
And then I compared the performance of last two years.This way I have prepared the  Customer Performance Report.

and also by using DAX formula I have created measures to calculate Net sales by countries for individual years.
and also the target for 2021 and then compared the difference between the Actual net sales and Target.

I have used Pivot table,conditional Formating,Various other formatting Options to make the report beautiful and easy to understand.

