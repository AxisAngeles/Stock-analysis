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

The upper graph shows different annual returns for each stock in 2017 and 2018.


### Challenges and Difficulties Encountered
Regarding the overall challenge, we've encountered some technical difficulties during the making of this summary, mainly at this md coding, which was adress with further investigation and, lets face it, trial and error.

There's also a remmaining challenge in finding a concrete answer to FEVER's results. This is why the next steps should also consider working on differente variables like the funding timming or average donation.

#
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. It does seems to be a seasonality involed when launching successfull campaigns.
  2. Failed campaigns have an even or flat distribution along the year, so there mush be other elements correlated to that outcome.

- What can you conclude about the Outcomes based on Goals?
  1. First, the initial line chart it's not sufficient to draw any significant conclussion.
  2. As expected, the higest goals are most likely to underperfom or fail.

- What are some limitations of this dataset?
  * It can allways be more helpful to have broader datasets, (i.e bigger campaign samples).
  * We have no information about the types of campaigns or about the backers.

- What are some other possible tables and/or graphs that we could create?
  * Using the same pivot table, we could do further research to compare campaigns lauched at simmilar conditions (dates or countries).
  * A box and whisker chart could also help to identify possible outliers for fair comparissons.
  * A dispersion diagram between goals and backers could help us identify the different reach of each campaign: was it funded by few backers with high contributions? or was it funded by many people?
