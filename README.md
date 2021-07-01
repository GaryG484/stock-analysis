# **Refactoring All Stock Analysis Subroutine**

## Overview
While refactoring the subroutine *‘AllStocksAnalysis’* I had three goals: to simplify the coding so that it performed faster, to reorganize the coding while adding explanatory comments to increase its clarity for other coders, and to modify it so it could work for other projects in the future with a broader data sample. To do this I had to change most of my variables and index loops, and separate other subroutines that I had originally running in tandem with my master code. Adding more comments not only added more clarity to the code for others, but also enabled me to better understand the code and modify it for better performance.

## Results
##### **After refactoring the subroutine, I managed to speed up the process by 0.52 seconds on the 2018 stock analysis, and .48 seconds on the 2017 stock analysis.** 

### *2018*
#####	Before refactoring the code for 2018 stock took 2.395 seconds to run, after refactoring the code runs in 1.875 seconds.

![alt text](https://github.com/GaryG484/stock-analysis/blob/main/Resources/VBA_Challenge_2018.PNG)

### *2017*

![alt text](https://github.com/GaryG484/stock-analysis/blob/main/Resources/VBA_Challenge_2017.PNG)

##### Before refactoring the analysis for 2017 stock took 2.315938 seconds to run, after refactoring the code runs in 1.835938 seconds. 
##### The code is sleeker and easier to understand even without the several comments I added to explain it. Furthermore, it is far more useful as a tool for the future instead of a one-time piece of code for this specific project while also running faster and using fewer resources. 
## Summary
##### There were several advantages to refactoring the code. Not only does it run faster, but the code is also far simpler and easier to understand. It has a better order so that the code flows in a more logical way. There are more comments to explain any parts of the code that are not obvious, and it also looks neater when you first glance at it. Finally, it also allows us to use the subroutine for multiple stocks instead of just the ones in this data set.  There are several disadvantages, however.  Refactoring the code cost plenty of man hours where it sometimes did not feel like I was accomplishing anything. The code may have been ugly to begin with, but it worked which is not nothing. Many times, I wrote a line of code, deleted it, re-wrote it, deleted it again, re-wrote it the same way it was in the beginning, only to delete it once more. While the project is much more utilitarian now, if it was more a project that had less usefulness on a broader scale, then this would not have been worth it. Refactoring would only be advantageous on code that has a broad range of utility. 
