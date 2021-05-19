# Introduction:

* For this project it's required to pull some data from the Qunadl API.
* Qaundl is currently the most widely used aggregator of financial market data.
* Qaundl has a large number of data sources, but, unfortunately, most of them require a Premium subscription. Still, there are also a good number of free datasets.
* For this project, we will focus on equities data from the Frankfurt Stock Exhange (FSE), which is available for free. We'll try and analyze the stock prices of a company called Carl Zeiss Meditec, which manufactures tools for eye examinations, as well as medical lasers for laser eye surgery: https://www.zeiss.com/meditec/int/home.html. The company is listed under the stock ticker AFX_X.
* While there is a dedicated Python package for connecting to the Quandl API, we would prefer that using the requests package.

# STOCK TREND ANALYSIS

The following are the tasks achieved while analysis:
1) Collect data from the Franfurt Stock Exchange, for the ticker AFX_X, for one whole year
2) Convert the returned JSON object into a Python dictionary.
3) Calculated what were the highest and lowest opening prices of the stock in this period.
4) Determined what was the largest change in any one day (based on High and Low price)
5) Calculated what was the largest change between any two days (based on Closing Price)
6) Determined what was the average daily trading volume during this year.

