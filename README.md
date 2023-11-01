# DAVE3625Oblig2
|Subject|Student Name |Date |
|-------|-------------|-----|
|DAVE3625| Jon Petter Wiig & Freya Dong| 01.11.2023| 
### Introduction: 
----
In oblig 2 there were two different options for the task. To create a prediction algorithm for tesla stock.  Or to predict where there is most likley for a passenger to enter the bus. 
We decided to go with stock prediction. 

----
For the stock prediction we decided to go with the tesla stock. We decided to the newer data from Yahoo! stocks.  Theese stocks are from when TSLA opened for public trading in june 2010 to October 23rd 2023. This means that we have a lot of data to to train with. The data itself consists of 7 coloumbs and about 3000 entries. 

The columba are:
- Date (Object): The dates the stock were trained
- Open (Float): Opening price for one stock
- Close (Float): Closing price for one stock for when the price is closed 
- Adj Close (Float): Adjusted closing price
- Volume (int64): Number of stocks traded in a day
-----
#### Use of the data

We primarly trained our data on date and the closing time. To train our data we used polonymal regression. polonymal regression is usually used when there are non-linear data. a stock goes either up or down based on the day. It becomes more accurate to use polonymal instead of linear, as linear compears two different points. However, poloynmal takes in multiple parameters and creates a more accurate prediction. 
