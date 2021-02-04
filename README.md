### Timeseries data ingestion and plotting of stock quotes

**Input:**

3 CSV files, each containing : open, close, high, low for AMZN, AAPL, MSFT at 5m internvals

**Expected**

- Create a ROR app that ingests this data via file upload
- Decide on table schema for storing the time series data
- Create a page to show the timeseries data on graph
    - Allow for aggregation on the time axis (eg. hourly, daily)
        - On aggregation
            - Median of following values in interval : open, close, high, low
            - Sum of following values in interval: volume
    - Allow filtering on the ticker symbol and skipping weekends
- Frontend should be in react or angular
- Things we will look for
    - Proficiency in ruby and ruby on rails
    - Proficiency with Activerecord, data modeling and SQL
    - Code clarity (without using excessive commenting)

**Questions to answer but not required to implement**

1. If you have to support 100x the volume of data what would you change in the architecture, schema etc ?
2. How will you support realtime ingestion of a data feed of ticker data ?
