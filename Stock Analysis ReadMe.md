# Stock Analysis
## Purpose
The purpose of this project is to create code that analyzes various stocks and assesses performance of each to drive investing decisions. This code takes raw data from stock marks and analyzes each line to dictate if the particular stock being assessed is still being covered in the data or if the summarization is complete. 

## Results
### 2017 
this was a good year for the green stocks in question. Four of the twelve stocks analyzed saw over a 100% gain with eleven of twelve seeing positive returns and only one stock seeing losses. 
[2017 image]

### 2018 
2018 was not nearly as good of a year as 2017 with 10 of 12 stocks seeing losses. The best investors could have hoped for in this year was an 84% retirn by selecting the correct stock 
[2018 image]

### Original code
The original code built in this module ran fairly quickly at around 4 secconds. 
[Original code image]


### Refactored code
after refactoring the code we can see that it now runs in less than a quarter of the time of the original code. 
[Refactored code image]

### Advantages of refactored code
By refactoring the code we are able to run the process much faster. This means that if we were to greatly increase the amount of stocks we are analyzing we would be able to do so without drastic slow downs in the process or leveraging too much system resources. This applys to the original script because without the indexing of the ticker we would have to have the system manually check all data each time there was a new ticker which would create a very long and unsustainable process as the number of stocks assessed increased 
