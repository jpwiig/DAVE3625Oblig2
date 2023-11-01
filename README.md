# DAVE3625Oblig2
|Subject|Student Name |Date |
|-------|-------------|-----|
|DAVE3625| Jon Petter Wiig & Freya Dong| 01.11.2023| 
### Introduction: 
----
In Oblig 2 there were two different options for the task. To create a prediction algorithm for Tesla stock.  Or to predict where it is most likely for a passenger to enter the bus. 
We decided to go with stock prediction. 

----
We were tasked to use the Tesla stock (TSLA). We decided to use the newer data from Yahoo! Finance (https://finance.yahoo.com/quote/TSLA?p=TSLA).  These stocks are from when TSLA opened for public trading in June 2010 to October 23rd 2023. This means that we have a lot of data to train with. The data itself consists of 7 columns and about 3000 entries. 

The columns are:
- Date (Object): The dates the stock was traded
- Open (Float): Opening price for one stock
- Close (Float): Closing price for one stock for when the market was closed. 
- Adj Close (Float): Adjusted closing price
- Volume (int64): Number of stocks traded in a day.
-----
#### Use of the data

We primarily trained our data on the date and the closing price. To train our data we used polonymal regression. 

----
#### Polonymal regression

Poloyminal regression is a way of using regression on non-linear data to predict future data(https://www.analyticsvidhya.com/blog/2021/07/all-you-need-to-know-about-polynomial-regression/), linear regression works only on linear data. Stock is not linear, it varies. hence we use polynomials to make predictions of non-linear data easier. 

polonymal regression is usually used when there are non-linear data. a stock goes either up or down based on the day. It becomes more accurate to use polonymal instead of linear, as linear compares two different points. However, a polynomial takes in multiple parameters and creates a more accurate prediction. 
