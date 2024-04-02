---
layout: default
title:  "02806 Assignment 2"
date:   2024-03-19 21:48:30 +0100
categories: Update
---

<link rel="stylesheet" type="text/css" href="path/to/your/css/file.css">


# Assignment 2 for 02806 Social Data Science and Visualization
This assignment is made by students s204606, s194299 and s185382. 

## Introduction to the assignment
This assignment compares the two police districts Tenderloin and Central, in north eastern San Fransisco, based on the dataset SF Crime Data. The districts are specifically compared for the crime category 'DRUG/NARCOTIC', where we visualize and study the difference between these two districts in regards to the crime category over time, for weekdays, and visualize where the crimes have happened in the districts. These specific districts are compared as there is a much higher drug and general crime activity in Tenderloin than in Central, despite Tenderloin being much smaller in size, and the districs bordering each other. 


## Bar chart of the yearly number of 'DRUG/NARCOTICS' crimes in Tenderloin and Central
The following bar chart shows the development of the drug/narcotic crimes in the two districts, where the number of incidents are not normalized, but shown as real numbers to convey the difference between the chosen districts. 
![Bar chart of Tenderloin and Central](https://github.com/AndersNielsen77/AndersNielsen77.github.io/blob/main/docs/assets/images/newplotnewnewnew.png?raw=true)

From the bar chart it appears that crimes related to drugs and narcotics are noticeably higher in Tenderloin than in Central. There is a general declining trend after this peak, which seems to further decrease after 2014. According to Wikipedia, drug crimes in Tenderloin have escalated since 2007, and parking in both sides of streets in the district was banned in early 2014 in an attempt to curb some of the narcotics crimes [1]. The decrease timplies hat some of the city's regulations and attempts to mitigate crime has worked, as the drug crimes in Tenderloin decrease after the law concerning parking in 2014. The peaks and decline in drug use in the Central district, however, does not match the trends seen for Tenderloin. Instead, drug use in Central peaks both in 2008 and 2014, demonstrating the difference in drug use between the two districts.  

## Map plot of the incidents of drug/narcotics crimes
The next visualization shows the coordinates for incidents of drug use, where higher concentrations of incidents are represented by a red color. The visualization shows the change in locations for drug use from 2007 to 2017. 

<iframe src="/Newnewnewdrugsmap.html" height="500" width="700"></iframe>

As seen on the map above, Tenderloin district is quite consistently very concentrated with drug crimes, meaning that drug use has been reported in high volumes. When zooming in on the district, it is clear that there are no particular areas where drug use is more frequent, but all streets have dots representing places of drugs or narcotics crimes. This does not vary over the years. For the central district, the narcotics crimes are more spread out, with the streets closer to Tenderloin showing higher concentrations of crimes. There is also an area where Broadway crosses Columbus Avenue where drug crimes are more frequent, which is consistent for the whole time period. There are some bars in the area which might explain the crimes, but the more likely explanation is both these streets are quite large, and therefore probably more frequented by police, increasing the risk of being arrested. There are slight variations for the different years when looking at the concentration of drug crimes for the Central district, but nothing major. 

## Bar chart of the 8 most frequent words in the description of crimes across the two districts 
The interactive Bokeh graph below presents the eight most frequently used words in the descriptions of drug/narcotic incidents recorded in the Tenderloin and Central districts. These words were identified by averaging the TF-IDF scores from both districts. The TF-IDF algorithm was applied to the combined text from the incident descriptions in the Tenderloin and Central districts.

{% include FREQ.html %}

The graph indicates that 'cocaine' and 'rock' are used more frequently in the Tenderloin district descriptions, significantly more so than in the Central district. Conversely, the Central district exhibits higher frequencies of the words 'narcotics,' 'paraphernalia,' 'amphetamine,' and 'marijuana' compared to the Tenderloin. When taking into account that general drug-related crime counts are much higher in the Tenderloin compared to Central, the frequency of certain words used in crime reports does not necessarily indicate that Central has higher concentrations of those crimes. This factor should be considered when interpreting the data from the Bokeh graph. It's also reflected in the heatmap provided above, which visualizes the intensity of drug-related incidents geographically. The word data can however, be used to get an indication of which type of drug crime is most apparent in a given district. 

### Sources 
1. "Tenderloin, San Fransisco", Wikipedia, The Free Encyclopedia, Wikimedia Foundation, 13th March 2024, https://en.wikipedia.org/wiki/Tenderloin,_San_Francisco
2. "tf-idf", Wikiepdia, The Free Encyclopedia, Wikimedia Foundation, 17th March 2024, https://en.wikipedia.org/wiki/Tf%E2%80%93idf