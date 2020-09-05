# VBA of Wallstreet

## Overview of Project

### Purpose

The purpose of this exercise was to refactor the code from the Module 2 solution to help Steve potentially expand his dataset in the future without hindering performance.


## Results

After refactoring the code and creating arrays and a ticker index and watching the code cycle through in the Locals window it became pretty obvious of the advantages using an index, especially if you have a large dataset.

![Arrays:](resources/Arrays.png)

Looping through the arrays using the ticker index and then using the ticker index to output the results was a more efficient way to write this code compared to the code written in the module.

![Outputs:](resources/Outputs.png)

When I compared the results of the execution times of the 2017 & 2018 stocks from both the original code from Module 2 and the refactored code in the VBA challenge there was a significant difference. If we were looking at thousands of stocks instead of 12 it would play a big factor in which code we used.

Module 2 Execution Times:

![2017 Module 2:](resources/green_stocks_2017.png)
![2018 Module 2:](resources/green_stocks_2017.png)

VBA Challenge Exection Times:

![2017 Refactored:](resources/VBA_Challenge_2017.png)
![2018 Module 2:](resources/VBA_Challenge_2017.png)

Results from 2017 and 2018 Worksheets

![2017 Stocks:](resources/All_Stocks_2017.png)
![2018 Stocks:](resources/All_Stocks_2018.png)

## Summary



### Links
