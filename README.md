# An Analysis of Stock Performance
## *The Goal and Methodology*
### In this analysis we wanted to identify high performing stocks worth investing in to produce good returns. We built macros to pull data, make calculations, and format for easy analysis.
The things we wanted to know in particular are:
1. How did different different stocks perform by year?
2. Will our code run efficiently with a higher stock count?
---
## *Stock Performance by Year*
### We built our code to allow for user input to determine which year we analyze.
<br>

What we learned ***2017*** 

1. 2017 was a good year for these stocks
2. The best performing stocks were *DQ* and *SEDG*

What we learned ***2018***
1. This was a bad year for our stocks
2. Only 2 stocks had a positive return: *ENPH* and *RUN*
<br>

These findings would suggest that *ENPH* would be the best stock to invest in! It has the highest rate of return for the 2 years we analyzed.


---
## *Refactoring our Code*
### To make sure we would be able to carry this tool forward and anyalyze bigger samples, we refactored our code. The goal was to increase performance by decreasing our run times.
What we accomplished:
1. When running the code for the 2017 year analysis we had a huge performance increase. We increased from a 0.516s runtime to a 0.094s runtime!
2. When running the code for the 2018 year analysis we had a huge performance increase. We increased from a 0.523s runtime to a 0.078s runtime!

We accomplished this performance increase with 2 major code changes:
1. We used a named variable for our index and used that to iterate more quickly.
2. We used segmented loops for our multiple arrays resulting in quicker looping of our list.

Refactoring the code also incorporated the formatting step to the analysis! So instead of 2 macro buttons we simplified the tool for end users by consolidating it into a 1-step process!

*The <ins>Original 2017</ins> Runtime*

![Original code for 2017](https://github.com/05Perseus/Stocks-Analysis/blob/main/Resources/2017%20Runtime_Original.png)

*The <ins>**Refactored 2017**</ins> Runtime*

![Refactored code for 2017](https://github.com/05Perseus/Stocks-Analysis/blob/main/Resources/2017%20Runtime_Refactored.png)

*The <ins>Original 2018</ins> Runtime*

![Original code for 2018](https://github.com/05Perseus/Stocks-Analysis/blob/main/Resources/2018%20Runtime_Original.png)

*The <ins>**Refactored 2018**</ins> Runtime*

![Refactored code for 2018](https://github.com/05Perseus/Stocks-Analysis/blob/main/Resources/2018%20Runtime_Refactored.png)

---
## *Conclusion*
We learned several things from this analysis.
1. 2017 was a much better year for our stocks
2. If you must only choose one stock, choose *ENPH*!
3. The refactored code will work drastically better for our end users and resulted in a more efficient tool

This excercise was a great advantage to our end user. We went from decent code and a 2 button process to great code and a single touch process. I highly recommend refactoring to include index variables and segmented loops for greater efficiency. 
