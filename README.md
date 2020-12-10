# VBA

## Overview of Project 
The project is to help Steve analyze the stock performance for his parents   

### Project Purpose 
Help Steve compare the stock performance across a list of tickers in both 2017 and 2018

## Results

### 2018 vs 2017
Stocks which were traded more in 2018 vs 2017 : DQ, ENPH, HASI, RUN, SEDG, TERP, VSLR
Stocks which saw higher returns in 2018 vs 2017: Run, TERP

### Analysis of 2018 Stock Performance 
![](https://github.com/esaer/VBA/blob/main/2018.PNG)

### Analysis of 2017 Stock Performance
![](https://github.com/esaer/VBA/blob/main/2017.PNG)

### Execution times of the original script and the refactored script 
Execution times for 2018 of the refactored script is 0.59 seconds, which is much quicker than that of the original script which is 14.55 seconds. 
Execution times for 2017 of the refactored script is 0.14 seconds, which is much quicker than that of the original script which is 93 seconds. 

## Summary 
- What are the advantages and disadvantages of refactoring code 
The advantages of the refactoring code is that it saves a lot of time. It runs much quicker than the original code. 
The disadvantages is that the arrays in the refactoring code might take extra memory. 

- How do these pros and cons apply to refactoring the original VBA script?
Because the original code loops over all the rows multiple times, it's much slower. Therefore by creating arrays in the refactored code allows us to run the code faster. 

