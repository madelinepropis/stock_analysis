# VBA Challenge

## Overview of Project

The VBA Challenge had two parts: DQ Analysis anad All Stocks Analysis. There are two datasets for the years 2017 and 2018. In the analysis, twelve stocks are analyzed based on volume and close prices for each day of the year. The purpose of this analysis was to use VBA skills in a real-world situation.

## Results

For the DQ Analysis, I wrote a macro to determine yearly the total daily volume and return for a stock, DQ. The macro loops through the 2018 dataset to find the first and last rows with ticker "DQ" and determine the total volume of all rows with ticker "DQ". 

The next part of this project was the All Stocks Analysis. In this part, there are twelve stocks being analyzed. This macro allows the user to input the year of the data. This code also incorporates arrays to give each of the twelve tickers an index number. The macro loops through the year that the user inputs to find total volume, starting price, and ending price for each stock and makes a list with each stock and their total volumes and return rates. At the end of the macro, a message box pops up with the time it took for the code to run.

The All Stocks Analysis was refactored in order to reduce length of the code. The smaller and more concise the code, the faster and more efficient it will run. The goal of the refactored code was to reduce time to run the code. In order to reduce the length of the code, I created four additional variables which were used in arrays to loop through the data. The refactored code ran faster than the original code. 

### Before Refactored Code

When running the All Stocks Analysis macro for 2017 before the code was refactored, it took about 0.8398 seconds to run.  

![2017_RunTIme_Before](https://user-images.githubusercontent.com/109561408/183807864-d07b5205-33d0-4149-baa6-d10acc8283bd.png)

When running the All Stocks Analysis macro for 2018 before the code was refactored, it took about 0.8359 seconds to run.

![2017_RunTIme_Refactored](https://user-images.githubusercontent.com/109561408/183807914-dc73f68d-8294-4b5e-8273-977775165413.png)

### After Refactored Code

When running the refactored All Stocks Analysis macro for 2017, it took about 0.1641 seconds to run. 

![2018_RunTIme_Before](https://user-images.githubusercontent.com/109561408/183807934-4d7b5b34-404d-4d9b-9377-b8f2e07984c8.png)

When running the refactored All Stocks Analysis macro for 2018, it took about 0.1406 seconds to run. 

![2018_RunTIme_Refactored](https://user-images.githubusercontent.com/109561408/183807956-9bf28dea-9b6e-47e6-b30b-33854189e753.png)

## Summary

For future projects, it is important to note that there are advantages and disadvantages to refactoring code. One advantage is that refactoring can drastically reduce the time it takes to write a code. One disadvantage of refactoring code is that in many industries, it is more expensive than writing a code from scratch.

In this project, one advantage for refactoring code was to save time. The main advantage was the time taken to run the code was reduced. This time decrease would be essential if the analysis ran for all stocks in the USA. One disadvantage of refactoring code in this project was understanding and debugging issues. 
