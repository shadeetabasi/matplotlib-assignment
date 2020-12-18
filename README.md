# Matplotlib Assignment: Pymaceuticals
This repository will house the Pandas homework assignment due on December 19, 2020.

## Files and directories within this repository include:

### Pymaceuticals
* pymaceuticals_starter.ipynb
* Data Folder
  * Mouse_metadata.csv
  * Study_results.csv
### Images
  * Contains images within this README

# Pymaceuticals : Assignment Details & Summary
![Pymaceuticals](https://github.com/shadeetabasi/matplotlib-assignment/blob/main/Images/Laboratory.jpg)

**Summary:** 
While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.


As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

**Observations:** 
* Overall, Capomulin appears to be effective in decreasing tumor volume over time. However, Ramicane appears to be associated with the smallest tumor volume/size out of four treatments - Capomulin, Ramicane, Infubinol, and Ceftamin.
* There appears to be one outlier in the Infubinol dataset - a mouse with a tumor volume below 36.83 - which would require further investigation.
![Pymaceuticalsboxplot](https://github.com/shadeetabasi/matplotlib-assignment/blob/main/Images/pymaceuticals_boxplot.png)

* There appears to be a positive correlation between mouse weight and tumor size - as indicateed in the final linear regression analysis conducted for the Capomulin drug regimen. This may indicate that either treatment was less effective in larger/overweight mice or simply that bigger mice have bigger tumors. We would need to look at change in tumor size over time for mice within different weight buckets to have a definitive answer here.
![Pymaceuticalslinearregression](https://github.com/shadeetabasi/matplotlib-assignment/blob/main/Images/pymaceuticals_linearregression.png)
