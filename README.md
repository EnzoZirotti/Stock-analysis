# Stock-analysis
### Overview of Project
The goal of this project was to help Steve look at the full dataset for the entire stock market. The code that was given to us only works for a dozen stocks but not thousands.

![Screenshot](/Resourses/Old_Code.png)

We then needed to refactor this code so this way we could look at a larger dataset at a faster speed.
 
### Results
 
The results I have found were that the refactored code was much faster that the old code.

![Screenshot](/Resourses/VBA_Challenge_2017.png)

![Screenshot](/Resourses/VBA_Challenge_2018.png)

The reasoning I have for this is that in the original code it's checking the 3000 rows 12 times where as with the new code I'm going through the 3000 rows just once. The times for the 2017 and 2018 were (.3046 and .2539). This is 2 seconds faster then what the nonrefactored code results were. ![Screenshot](/Resourses/Results_oldcode.png)
 
## Summary
 The advantages of having a refactored code would be to have a faster speed time for a larger scaled database since this is the end goal in refactoring code. However a disadvantage to this is that refactoring a code can confuse others that might be likley to work on this with you. 
 
 The advantage to refactoring this code is that now it is much faster and ready for a larger scale code. Although now with this code it is specific to only 12 tickers and not more which make this a disadantage if you were to run this for your first time expecting it to be able to be copy pasted for larger scale. If we were to make this for grand scale we would need to adjust this a little by changing the amount of tickers and their arrays.
 
 
