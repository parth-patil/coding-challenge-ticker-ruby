### Timeseries data ingestion and plotting of stock quotes

**Input:**

3 TSV (tab separated) files, each containing stock price data for 3 stock symbols.

Following is sample data in the TSV files:-

|symbol|	timestamp|	price|
|------|-------------|-------|
|AAPL|	1601551740|	117.451|


**Explaination of input data columns**
*Symbol:* Ticker symbol eg (AAPL, MSFT etc)
*Timestamp:* Unix timestamp of the data point
*Price:* Stock price at that point in time

**Expected**

- Create a ROR app that ingests this data into the database via form based file upload
- Decide on table schema for storing the time series data and create the required active record model
- Create a page to query the timeseries price data for a given symbol
    - Provide a drop down to select the ticker symbol
    - Proivde a drop down to select the aggregation on the time axis at hourly and daily
    - When aggregating over hour and day use Avg of the *price*

- Things we will look for
    - Proficiency in ruby and ruby on rails
    - Proficiency with Activerecord, data modeling and SQL
    - Code clarity (without using excessive commenting)

**Good to have (optional)**
- Frontend in react or angular

**Questions to answer but not required to implement**

1. If you have to support 100x the volume of data what would you change in the architecture, schema etc ?
2. How will you support realtime ingestion of a data feed of ticker data ?
