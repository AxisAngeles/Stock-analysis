# **Stock-analysis with VBA**

### Purpose
The following document will show the results of the statistical analysis for a given number of potencial stocks and their respective volumes and returns during the years 2017 and 2018.


## **Process Overview and Conclusions**

### Working methodology
We first improved the 1st deliverable to our client, which was an automatic process to gather stock data in an easy-to-read chart with the main results for each of the analized stocks.

Thus, the code behind the analysis resulted on a 0.023 seconds time improvement regarding data processing time, as shown on the following images.

**Original:**

![Original_Process_Time](https://github.com/AxisAngeles/Stock-analysis/blob/main/Challenge/Resources/Original_2018.PNG)

**Improved Code:**

![Improvded_Process_Time](https://github.com/AxisAngeles/Stock-analysis/blob/main/Challenge/Resources/VBA_Challenge_2018.png)

_NOTE: This may not seem like a hughe time saving improvement, but as the data set increases, the changes will add up to a several minutes difference._


### Analysis Results
For any investment, there's usually a lot of ellements to be taken into account: risk adversity, timming, capital, etc. However, for this analysis we'll make our recommendation based on the annual return for 2017 and 2018 which are shown on the following chart:

**Annual return for analyzed stocks:**
![Annual_Return](https://github.com/AxisAngeles/Stock-analysis/blob/main/Challenge/Resources/AllStock_Analysis.png)

The upper graph shows different annual returns for each stock in 2017 and 2018. In general we can highlight that 2018 was a complicated year for almost each stock with the exception of ENPH and RUN which had a positive return during both years, specially RUN that actually performed better un 2018.

This is why, we may conclude that investing in both **ENPH** and **RUN** should be a reliable option for our clients, after all, _diversification_ is allways a good advice.

### Summary
What are the advantages or disadvantages of refactoring code?
How do these pros and cons apply to refactoring the original VBA script?
