# Challenge Overview

Module 2’s challenge was to take our original code that found the total daily volumes and returns of the 12 stocks and refactor the code using arrays. The purpose was to see if the refactored code resulted in faster results. The theory being that using a tickerIndex to loop through the data only once and arrays to store the results as they were found would make the code faster.

# Results of Refactoring Using Arrays

The challenge was a success. The original code ran in about 1 second plus or minus a tenth of a second. The refactored code finished in about .14 seconds. The code ran in about a seventh of the time, which is a great improvement. 
  
Results from running 2017 Analysis:

![VBA_Challenge_2017](https://user-images.githubusercontent.com/95837693/148323908-5d47a950-35be-4645-8bb8-20323e9f9383.PNG)

Results from running 2018 Analysis:

![VBA_Challenge_2018](https://user-images.githubusercontent.com/95837693/148323915-e0d7ee83-5332-4906-a2e6-f07330d405a3.PNG)

# Summary of Advantages & Disadvantages

The advantages of refactoring code are that you can fine tune the process and make sure you are doing the task in the least possible steps, least loops through the data, and getting the fastest results. Refactoring gives you a chance to look at your code and make sure you aren’t repeating yourself in any of the code and see if there are any better ways to do what you have already coded.
  
In this challenge, I found that the refactored code did in fact run faster than the original code. The reason for the faster code is that the results wrote to arrays in one pass through the data instead of looping through the rows 12 times to find each of the volumes, starting prices and ending prices. These data sets contained about 3,000 rows. Excel can hold over 100,000 rows, so if we were using a larger dataset the speed improvement from the original code would be even more remarkable.
