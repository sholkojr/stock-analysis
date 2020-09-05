# Analysis of Select Clean Energy Stocks between 2017-18

## Objective

To perform an analysis of select clean enery stocks with opening, closing and trade volume data from 2017 and 2018.  A tool was developed in VBA for the client to quickly summarize the data to understand profit/loss and trading volumes of the stocks for both years and to enable the client to perform further analysis with more data.

## Results

### Development of the Analysis Tool

The tool was developed by creating variable arrays to add up the volume and determine the opening and closing price of each stock ticker. The tool was initially developed to track and analyse one stock and year of interest to the client ( stock "DQ" during the year 2018) and then the code was revised to include all stocks and multiple dataset representing different years (2017 and 2018).  There was a third revision to refactor the code to make the tool run more efficient, flexible and capable for further use (addiitonal stock data).

### Description of Algorithm

A for loop was developed to cycle through the data.  Each loop would test to see if the ticker name had changed (signalling the first stock entry and opening price) or was going to change (signalling the last stock entry and closing price) and would total the volume traded between the opening and closing entry in the data.

![Code of Calcs](/Resources/VBA_Code_Calc.png)

The summarized data would then be automatically displayed in a table generated by the VBA Code.  Buttons were inserted to provide a handy interface to run the scripts to generate the results.

![Code of Output](/Resources/VBA_Code_Output.png)

### Execution of Analysis Tool

When the script is executed, the user is prompted to enter the year to analysed, in this case either 2017 or 2018. 

![Year Input](/Resources/Screenshot_Year_Input.png)

Then the chart is populated and a run time execution dialog box is opened.  The below show an example of the runtime results for 2017 and 2018 year executions

### Output for 2017

![2017 Summary Output](/Resources/All_Stocks_2017.png)

### Original Code Runtime for 2017

![2017 Runtime](/Resources/VBA_Challenge_2017_prerefx.png)

### Refactored Code Runtime for 2017

![2017 Runtime](/Resources/VBA_Challenge_2017.png)

### Output for 2018

![2018 Summary Output](/Resources/All_Stocks_2018.png)

### Original Code Runtime for 2018

![2017 Runtime](/Resources/VBA_Challenge_2018_prerefx.png)

### Refactored Code Runtime for 2018

![2018 Runtime](/Resources/VBA_Challenge_2018.png)





