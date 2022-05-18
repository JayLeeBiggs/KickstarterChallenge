# Kickstarting with Excel


## Overview of Project
The Kickstarter Project (KP) analyzed the success and failure of Kickstarter campaigns based on
a number of categories eg. Television, Theater, etc. Further, the KP took a deeper at goals, 
funding, date of the launch of the campaigns, etc. Multiple analyses were performed based on the KP's
stated goals and desired outcomes. The commissioning of the KP was at the request of Louise.

### Purpose
The specific purpose of this KP was to examine the performance of Louise's play, Fever. Louise wanted to 
know how her Kickstarter campaign performed when compared against other kickstarter campaigns based on
launch dates and funding goals.

## Analysis and Challenges
The analysis can be broken into two components - Outcomes Based on Launch Date and Outcomes Based on Goals.
A third subsection will examine challenges and difficulties in performing the analyses.The analysis sub-sections, 
aka components, will discuss the findings of the analyses. 

### Analysis of Outcomes Based on Launch Date
To generate the analysis of outcomes based on launch date the data was cleaned and prepared:
1. The category / sub-category column was separated. 
2. Dates were converted from a Unix format into the Long Date Format for Excel. The conversion was made
using the code: =(((Cell/60)/60)/24)+DATE(1970,1,1).
3. The Dates were then used to create an additional column, Years, using the formula:  Year(Cell).

Next, a Pivot Table was created using Category and Year as filters. Finally, a Pivot Chart was made to create
a visual presentation of the data for easy consumption.


### Analysis of Outcomes Based on Goals
To generate the analysis of outcomes based on goals, a series of Countif statements were utilized to gather
and populate cells in a new worksheet. Further, the goals were sorted into specific fundraising levels to allow
for an analysis based on the amount requested, goal. 


### Challenges and Difficulties Encountered
One challenge I encountered was in using the Countif formula. It took me a while to get all of the parentheses
in the correct location. Then, after copying and pasting the formula, I realized that I had forgotten to lock
the reference cells, creating inaccurate information in the copied formulas. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion that can be drawn from the data would be that the campaigns most likely to succeed are
launched in May or June. 
The second conclusion is that the more distance from the ideal months a campaign is launched, the more likely
it will fail. 

- What can you conclude about the Outcomes based on Goals?


- What are some limitations of this dataset?


- What are some other possible tables and/or graphs that we could create?
