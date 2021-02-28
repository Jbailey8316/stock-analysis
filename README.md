# VBA Challenge
## Overview of Project
  The purpose of this VBA Challenge was to refactor a vba module to improve performance and scalability.
 
## Results
 By revisiting a written script; a coder can reevaluate an initial attempt at a block of code.  This could allow for better notation to help clarify the purpose of any given line or block of code.  It can offer the opportunity to find a more effective way to execute a script saving on computer resources and improving performance.  It could also offer an opportunity to add new functionality that wasn't previously considered or change the code to make it more scalable.  

By refactoring the provided code there was an increase in the amount of time it takes to perform the data collection as shown in the following images.

### Orginal Run Time vs Refactored Run Tiime For 2017 Stock Analsysis
![Original Time 2017](https://github.com/Jbailey8316/stock-analysis/blob/main/resources/2017%20Original%20Code%20Time.PNG)
![Refactored Time 2017](https://github.com/Jbailey8316/stock-analysis/blob/main/resources/2017%20Refactored%20Code%20Time.PNG)

### Orginal Run Time vs Refactored Run Tiime For 2018 Stock Analsysis
![Original Time 2018](https://github.com/Jbailey8316/stock-analysis/blob/main/resources/2018%20Original%20Code%20Time.PNG)
![Refactored Time 2018](https://github.com/Jbailey8316/stock-analysis/blob/main/resources/2018%20Refactored%20Code%20time.PNG)

  Refactoring this code allowed me to change the number of loops needed to compile the stock data.  Originally there were 12 total loops of the sheet data.  This was changed into a single loop of the sheet data.  On a small scale this has caused an increase in the time to compile the data, but should allow for better performance with larger amounts of data later on.  I also decided to eliminate an entire loop for formating the analysis sheet.  I was able to combine this loop into a previous loop which should improve performance.
  
## Summary
Refactoring code can provide many advantages.  From updating old functionality to run with new added changes or by improving the performance of a script.  These improvements can help reduce the amount of resources needed to run the code or program and increase it's efficiency.  It also gives a coder a good chance to review a written code to ensure there are no unintended bugs.  It could also allow an opportunity to clarify the notation across the code, making it easier to understand by both the original coder or anyone trying to interpret it.  On occasion, skills can change and revisiting an old code with new knowledge could allow for some improvements.

While refactoring can have several advantages, there are also some disadvantages that could be possible.  When changing an original code you could introduce unintended side affects across a project.  By modifying one section of code someone could accidentally break another code further down stream.  There is also the possibility of introducing new bugs or other problems into an already working code in an attempt to improve it.  
