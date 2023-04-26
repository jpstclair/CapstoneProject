# CapstoneProject - 

Stock prices from 2020 to 2022 and COVID

Author: James StClair - edited 4/19/2023

I want to analyze the difference in some stock market fields since COVID, and show whether, as a whole, they are trending upwards since then, or downwards, and make predictions based on the data obtained. 

Each of the csvs in the repository shows a table, with all of the dates shown as well as each open, close, and adjusted close of each company. Each of these csvs is labelled with the stock symbol of the company in question(for example, ALL is Allstate).

The csvs labelled Healthcare, Insurance, and Delivery are those same dates across each csv, and the close of each business day, to be able to compare the companies to each other better at the end of each day. 

Each jupyter notebook file contains a scatter plot of the company named(or all of the ones in that field, for Healthcare, Insurance, and Delivery).


Original Link to the data: https://www.kaggle.com/datasets/paultimothymooney/stock-market-data 


Viewable Overleaf Link: https://www.overleaf.com/read/szmdbwqxdxjx 

All sources cited from the report: 
References
1. Mehrotra, N.: The aftermath and impact of covid-19 on stock markets, https://www.forbes.com/sites/theyec/2023/02/10/the-aftermath-and-impact-of-covid-19-on-stock-markets/?sh=4bdb943ec120
2. Mooney, P.: Tstock market data(nasdaq, nyse, sp500),
https://www.kaggle.com/datasets/paultimothymooney/stock-market-data
3. Wang, K.M., Lee, Y.M.: Are life insurance futures a safe haven during covid-19?
Finance Innov. 2023 9(1), 13 (2023). https://doi.org/10.1186/s40854-022-00411-z

I used Microsoft Excel and Jupyter Notebook for this project, and made use of the following programs:
  Python
  pandas
  numpy
  matplotlib
  skicit-learn(sklearn)
  Microsoft Excel(as both excel sheets and csvs)
  
For making predictions based on the data, I used Polynomial Regression and Elasticnet, and used a line chart to show each company's stock price for the period of 2020 through 2022, as well as the Average for each field in that time period. 

![Deliverystockprice](https://user-images.githubusercontent.com/111580524/233685854-47f4bedd-a9bf-44d2-abab-1ff44a538659.png)

![InsuranceStockprice](https://user-images.githubusercontent.com/111580524/233685865-7e9e2c0b-a805-4b77-8cde-3516bb031835.png)

![Healthcarestockprice](https://user-images.githubusercontent.com/111580524/233685880-3f961667-7756-4fc0-9bd9-7a7aab3200b1.png)



![deliverytrain3](https://user-images.githubusercontent.com/111580524/233685642-6cb311fa-125d-4e7c-9d22-155c24d2f6ff.png)

![Healthcaretrain4](https://user-images.githubusercontent.com/111580524/233685760-0336f28a-6eb7-44bc-8973-687f332d4853.png)

![Insurancetrain4](https://user-images.githubusercontent.com/111580524/233685797-c9eb497f-e601-4156-8ff5-43e41585a235.png)
