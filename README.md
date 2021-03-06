# Kickstarting with Excel

## Overview of Project
This project analyzes a repository of kickstarter campaign outcomes by their launch dates and funding goals.

### Purpose
Louise's campaign is now closed and she was close to achieving her $10,000 goal. The purpose of this project is to provide Louise insight into how other closed campaigns fared in relation to their launch date and funding goals. There are over 4,000 campaigns in this dataset. However, the focus will be on Theater campaign outcomes relative to their launch date, and the outcomes of Play campaigns relative to their funding goals.

For the purpose of this project, we will look at the following:
* Theater Outcomes by Launch Date, excluding live campaigns
* Play Outcomes based on Goals

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The following chart provides an overview of the Theater campaigns based on launch date. While a majority of campaigns are successful, the month it is launched is important. More insight into this chart can be found in the **Results** section of this overview.
![Theater_Outcomes_vs_Launch.png](Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The following chart provides an overview of the Play campaigns with the Theater category, based on funding goals. Not all goals have a favorable outcome so special attention to failures vs. successes in each goal category is warranted. More insight into this chart can be found in the **Results** section of this overview.
![Outcomes_vs_Goals.png](Resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
A few challenges were encountered during this analysis:

**Excel**
* Charts 'disappear' on the worksheets. However, if I scroll down beyond the data and where the chart *should* be and then scroll back up - the chart is visible again. I had thought when I save it as a .png it actually removes the chart. In response I would recreate the charts only to find I had many of them on the same worksheet.

* Date: When I used the YEAR() on all Date Created Conversion and the dataset was filtered, it returned 1905. However, once I removed the filter it returned the correct year.

**Data**

Evaluating data with zeros (number of canceled plays) is always a concern. Often this requires further validation in order to ensure the data itself is correct. If there is doubt, the analysis yields no benefit.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  * For theatrical productions, it is more favorable to launch the campaign in May.
  * Avoiding October launches would be prudent as it has a high failure rate and low success rate. 

- What can you conclude about the Outcomes based on Goals?
  * Goals under $5,000 are more likely to succeed and least likely to fail. This is evident by the distance between successful percentages and failed percentages.

- What are some limitations of this dataset?
  * Insight into which closed campaigns were launched by experienced kickstarters. Repeatability by person or group could further identify successful patterns.
  * Definitions for "staff_picks" and "spotlight". Understanding these elements could also enhance the understanding of success vs. failure or canceled.

- What are some other possible tables and/or graphs that we could create?

  * Additional graphs for this dataset could include a combination of the two created for this project. For example, how do the successful outcomes with goals of less than $5,000 trend over launch month? The same could be done for failed campaigns to avoid a similar fate.
