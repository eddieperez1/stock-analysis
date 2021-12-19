# stock-analysis
## Overview of Project

Steve just graduated with finance degree. His parents are planning to invest in green energy. Steve want to find out which stocks are the best to invest. After creating VBA code to calculate Total Volume and Return of each stock, Steve is worried that the code may run too slowly with more stock data. Thus Steve has asked to refactor the code and make it more efficient. This project finds which stocks are the best to invest in. Also refactored vs original code are examined with advantages and disadvantages of each, and runtimes of refactored and original are compared.

## Results
### Calculation
The total volume and return were calculated by summing the volume over the year, and finding the starting price and ending price to calculate return. 
```
return = ending price / starting price - 1
```
### Stocks
The stocks in 2017 had mostly increases while one had a decrease of about 7%. The stocks in 2018 has mostly decreases excpet ENPH and RUN which had increases. ENPH and RUN had increases over 2017 and 2018. Thus Steve's parents should invest in ENPH and RUN.
![stocks2017](https://github.com/eddieperez1/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)
![stocks2018](https://github.com/eddieperez1/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

### Refactored Code vs Original Code Runtimes
The reactored code is much faster than the original code at least a second faster. The refactored code uses a single loop with arrays while the original code uses a nested loop.

**The Original Code Runtimes:**

![Original Code 2017](https://github.com/eddieperez1/stock-analysis/blob/main/Screenshots/originalCode2017.png)
![Original Code 2018](https://github.com/eddieperez1/stock-analysis/blob/main/Screenshots/originalCode2018.png)

**The Refactored Code Runtimes:**

![Refactored Code 2017](https://github.com/eddieperez1/stock-analysis/blob/main/Screenshots/refactoredCode2017.png)
![Refactored Code 2018](https://github.com/eddieperez1/stock-analysis/blob/main/Screenshots/refactoredCode2018.png)
## Summary
### Code Refactoring
Code Refactoring can increase the efficiency of code, and make it easier to work with. All of this makes it easier to fix bugs and makes it easier to read. Disadvantages to code refactoring are that code needs to be completely understood. If one is missing knowledge of the code, then it makes it challenging to refactor the code. Code refactoring can be time consuming.

Sources:

[Wikipedia](https://en.wikipedia.org/wiki/Code_refactoring)

[Anarsolutions](https://anarsolutions.com/code-refactoring-concept-analysis/)

### VBA Script
The pros to code refactoring the VBA script are faster runtimes, results are stored in arrays and only one main loop is used. Since the results are stored in arrays, conditionals can be applied to the results in the VBA script. Also one main loop makes code easier to read and makes it run faster. The con to code refactoring the VBA script would be time consumption. Since I wrote the code, I dont have to worry about not understanding the code. It is possible to have written the refactored code without writing the original code. 
