Download Link : https://programming.engineering/product/stat-3250-assignment-11/

# STAT-3250-Assignment-11
STAT 3250 Assignment 11
Background: The folder Stocks.zip contains nearly 300 les, each including daily data for a speci c stock, with stock ticker symbol given in the le name. Each observation includes the following:

Date = date information recorded

Open = opening stock price

High = high stock price

Low = low stock price

Close = closing stock price

Volume = number of shares traded

Adj Close = closing price adjusted for stock splits (ignored for this assignment)

The time interval covered varies from stock to stock. There are some missing records, so the data is incomplete. Note that some dates are not present because the exchange is closed on weekends and holidays. Those are not missing records. Dates outside the range reported for a given stock are also not missing records, these are just considered to be unavailable. Answer the questions below based on the data available in the les.

    Use the collective data to determine when the market was open from January 2, 2005 to December 31, 2014. (Do not use external data for this question.) Report the number of days the market was open for each year 2005-2014. (Include the year and the number of days in table form.)

    Determine the total number of missing records for all stocks for the period 2005-2014.

    For the period 2005-2014, nd the 10 stocks (plus ties) that had the most missing records, and the 10 stocks (plus ties) with the fewest missing records. (For the latter, don’t include stocks that have no records for 2005-2014.) Report the stocks and the number of missing records for each.

    Repeat the previous question, this time for the stocks with the greatest and least proportion of missing records during 2005-2014. Report the stocks and the number of missing records for each.

    Identify the top-10 dates (plus ties) in 2005-2014 that were missing from the most stocks.

    For each stock, impute ( ll in) the missing records using linear interpolation. For instance, if d1 < d2 < d3 are dates, and P1 and P3 are opening prices on dates d1 and d3, respectively, then we estimate P2 (the opening price on date d2) with

                        P2 =
                        	

                        (d3 d2)P1 + (d2 d1)P3

                        d3 d1

The same formula is used for the other missing values of High, Low, Close, and Volume.

Use the imputed values to recalculate the Python Index (see Assignment 10 for the formula) for the open dates in 2007-2013. (Remember that weekends and holidays are not open dates, so don’t impute those.)

    Find the Open, High, Low, and Close for the imputed Python Index for each day the market was open in October 2010. Give a table the includes the Date, Open, High, Low, and Close, with one date per row.

    Determine the mean Open, High, Low, and Close imputed Python index for each month in 2008-2012, and report that in a table that includes the month and year together with the corresponding Open, High, Low, and Close.

