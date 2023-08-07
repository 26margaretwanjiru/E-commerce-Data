# E-commerce-Data

# 1.0 Background
According to statista.com(https://www.statista.com/topics/871/online-shopping/#topicOverview), over the last few years, e-commerce has become an indispensable part of global retail. Like many other industries, buying and selling goods has undergone a substantial transformation following the advent of the internet, and thanks to the ongoing digitalization of modern life, consumers all over the world now profit from the perks of online transactions.

As global internet access and adoption rapidly increase, with over five billion internet users worldwide, the number of people making purchases online is ever-increasing. In 2022, retail e-commerce sales were estimated to exceed 5.7 trillion U.S. dollars worldwide, and this figure is expected to reach new heights in the coming years, the report further states.

In terms of the leading internet and online services companies worldwide 2022, by market cap, Amazon is the biggest consumer internet and online service company worldwide with a market cap of approximately 857 billion U.S. dollars as of December 2022. Amazon was ranked first among selected online companies operating in the retail, real estate, mobility, travel and hospitality sectors. The digital commerce platform Alibaba.com ranked second with a market cap of 233 billion U.S. dollars.

# 2.0 Objectives
The objectives of the analysis are;

What are the sales figures for each country?
What is the overall sales trend?
How many new customers are there each month?
When do customers make the most purchases?
Which is the best selling product in each country?
When were the largest orders made?
Which customers made the largest orders?

# 3.0 Data Understanding
Context Typically e-commerce datasets are proprietary and consequently hard to find among publicly available data. However, The UCI Machine Learning Repository has made this dataset containing actual transactions from 2010 and 2011. The dataset is maintained on their site, where it can be found by the title "Online Retail".

Content "This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers."

Acknowledgements Per the UCI Machine Learning Repository, this data was made available by Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.

The data contains 541,910 rows and 8 columns.

Variable Description

InvoiceNo: Invoice number that consists 6 digits. If this code starts with letter 'c', it indicates a cancellation. StockCode: Product code that consists 5 digits. Description: Product name. Quantity: The quantities of each product per transaction. InvoiceDate: Represents the day and time when each transaction was generated. UnitPrice: Product price per unit. CustomerID: Customer number that consists 5 digits. Each customer has a unique customer ID. Country: Name of the country where each customer resides.


![image](https://github.com/26margaretwanjiru/E-commerce-Data/assets/34502518/77392bd8-5259-4e85-9ec0-7bd608925be2)


# Understanding Recency, Frequency, Monetary Value

The concept of recency, frequency, monetary value (RFM) is thought to date from an article by Jan Roelf Bult and Tom Wansbeek, titled “Optimal Selection for Direct Mail,” published in a 1995 issue of Marketing Science.

If you are familiar with the Pareto Principle or the 80/20 rule, It states that 80% of the consequences come from 20% of the causes.

Thus, in the business case, RFM analysis often supports the marketing adage that “80% of business comes from 20% of the customers.”

The RFM model is based on three quantitative factors:

Recency: How recently a customer has made a purchase

Frequency: How often a customer makes a purchase

Monetary value: How much money a customer spends on purchases

RFM analysis numerically ranks a customer in each of these three categories, generally on a scale of 1 to 5 (the higher the number, the better the result). The “best” customer would receive a top score in every category.

These three RFM factors can be used to reasonably predict how likely (or unlikely) it is that a customer will do business again with a firm or, in the case of a charitable organization, make another donation.

# Curious?

If you are curious about some of the limitations of this model, consider checking the below link out;

https://cxmtoday.com/staff-articles/is-the-rfm-model-obsolete/#:~:text=Arthur%20Hughes%20popularized%20the%20RFM,monetary%20value%20a%20customer%20spends.

Disclaimer: This is a personal data analytics practice project purely for learning code. The views and opinions expressed in this analysis outcome are those of the authors and do not necessarily reflect the official policy or any other party.This article is for informational purposes only; please consult your advisor to determine whether this strategy is right for you.

It’s important to note that there are various moderating variables that affect all data, many of which might not have been captured in these datasets. As such, I used the data provided to practice my data tidying and plotting techniques.

