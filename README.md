# stock-analysis

**Green Stock Analysis**
---
_**Overview of Project**_
---
Analyze 12 green energy stocks for our client Steve to present to their parents. Showing the return rates for 2017 and 2018 with color coded cells to show which had a positive return and which had a negative return, to assist them in making a more informed decision. 

Buttons were also added in the worksheet so Steve can pull whichever year they would like to work with.

We took the original code and refactored to assist Steve with future use and running thousands of stock options and save time in executing the macro.
A timer was ran on the first set of code and the refactored code to see the elapsed time and if the refactored code made the macro run faster.

---
## Results
---
Refactoring the code we 3 new output arrays were added: tickerVolumes, tickerStartingPrices, and tickerEndingPrices.
tickerIndex was set as an integer using tickerVolumes(tickerIndex) to use the new output arrays in conjuction with the 12 ticker symbols in for loops to collect the information needed for the totalVolume and return rate on each stock. 

---
#
Refactored Code

![Refactored 1](https://user-images.githubusercontent.com/96508478/156894122-69dd22df-33b0-4357-ac12-84454424ffa7.png)
![Refactored 2](https://user-images.githubusercontent.com/96508478/156894131-def3b2d9-638b-4ddf-bd5b-605defdefb0a.png)

---
#
Run Time With Original Code

![Time_Original_2017](https://user-images.githubusercontent.com/96508478/156894177-9a09a030-6a92-4a2d-90b9-5e244f2bd205.png)
![Time_Original_2018](https://user-images.githubusercontent.com/96508478/156894180-3450da20-839e-4c6c-8fde-43ace257aa82.png)


---
#
Run Time With Refactored Code 

![Refactored_Time_2017](https://user-images.githubusercontent.com/96508478/156894203-d1ee0b84-067c-4a18-937e-673f764b40d7.png)
![Refactored_Time_2018](https://user-images.githubusercontent.com/96508478/156894206-333bd7e2-9caf-49b5-b376-47c2db87aa0d.png)

---
The run time between the orignal code and refactored code for 2017 shows a decrease in time of 64.7%
The run time between the orignal code and refactored code for 2018 shows a decrease in time of 67.2%

Those run time differences will help in the long run when it comes to running larger data sets.

---
##
Summary

#
Results

Looking at the numbers and seeing the large difference in run time it proves that refactoring the code makes a noticeable difference. Refactoring the code also makes it easier to read which is useful when going through and trying to find any errors made while making the code as well as it makes it easier for any future user of the code to edit and make changes.
Refactoring code also comes with its disadvantages one of them being you can ruin an already working code set. Reusing the original code in a new macro is a way to help prevent that from happening. Another disadvantage is the human time used to refactor the code and running into errors when trying to run the new code.


---

