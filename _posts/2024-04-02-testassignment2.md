---
layout: single
title:  "02806 Assignment 2"
date:   2024-03-19 21:48:30 +0100
categories: Update
classes: wide

---
<style>
  .container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-gap: 20px;
  }

  .column {
    background-color: #f0f0f0;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
  }

  .column h2 {
    margin-top: 0;
  }

  .column p {
    margin-bottom: 0;
  }

  .column-image {
    width: 100%; /* Adjust the width of the image to fill its container */
    border-radius: 5px; /* Optional: Add rounded corners to the image */
  }
</style>


# Assignment 2 for 02806 Social Data Analysis and Visualization
This assignment is made by students s204606, s194299 and s185382. 

<div class="container">
    <div class="column">
        <h2>Introduction to the assignment</h2>
        <p>This assignment compares the two police districts Tenderloin and Central, in north eastern San Fransisco, based on the dataset SF Crime Data. The districts are specifically compared for the crime category 'DRUG/NARCOTIC', where we visualize and study the difference between these two districts in regards to the crime category over time, for weekdays, and visualize where the crimes have happened in the districts. These specific districts are compared as there is a much higher drug and general crime activity in Tenderloin than in Central, despite Tenderloin being much smaller in size, and the districs bordering each other. Historically, Tenderloin has been a very poor neighbourhood, with subsidized housing and many immigrants moving to the area [1]. In contrast, the central district includes areas like Nob Hill, North Beach and the Financial District, all wealthy areas with luxury hotels and restaurants frequently visited by tourists [2].</p>
        <p>This assignment compares the two police districts Tenderloin and Central, in north eastern San Fransisco, based on the dataset SF Crime Data. The districts are specifically compared for the crime category 'DRUG/NARCOTIC', where we visualize and study the difference between these two districts in regards to the crime category over time, for weekdays, and visualize where the crimes have happened in the districts. These specific districts are compared as there is a much higher drug and general crime activity in Tenderloin than in Central, despite Tenderloin being much smaller in size, and the districs bordering each other. Historically, Tenderloin has been a very poor neighbourhood, with subsidized housing and many immigrants moving to the area [1]. In contrast, the central district includes areas like Nob Hill, North Beach and the Financial District, all wealthy areas with luxury hotels and restaurants frequently visited by tourists [2].  </p>
        <h2>Map plot of the incidents of drug/narcotics crimes</h2>
        <p> The next visualization shows the coordinates for incidents of drug use, where higher concentrations of incidents are represented by a red color. The visualization shows the change in locations for drug use from 2007 to 2017. 
        As seen on the map above, Tenderloin district is quite consistently very concentrated with drug crimes, meaning that drug use has been reported in high volumes. When zooming in on the district, it is clear that there are no particular areas where drug use is more frequent, but all streets have dots representing places of drugs or narcotics crimes. This does not vary over the years. For the central district, the narcotics crimes are more spread out, with the streets closer to Tenderloin showing higher concentrations of crimes. There is also an area where Broadway crosses Columbus Avenue where drug crimes are more frequent, which is consistent for the whole time period. There are some bars in the area which might explain the crimes, but the more likely explanation is both these streets are quite large, and therefore probably more frequented by police, increasing the risk of being arrested. There are slight variations for the different years when looking at the concentration of drug crimes for the Central district, but nothing major. 
        </p>
        <h2>Summary</h2>
        <p>This assignment analyzes crime data from two police districts, Tenderloin and Central, in northeastern San Francisco, focusing on the 'DRUG/NARCOTIC' category. Despite Tenderloin's smaller size, it exhibits significantly higher drug-related crime rates than Central. 
        <p>The first bar chart illustrates the yearly trends of drug/narcotic crimes, indicating higher incidents in Tenderloin. A decline post-2014 suggests effectiveness of city regulations, contrasting with Central's inconsistent trends.</p>
        <p>The map visualization depicts spatial distribution of drug crimes from 2007 to 2017. Tenderloin consistently shows concentrated drug-related incidents, whereas Central's incidents are more dispersed, with notable concentrations near Tenderloin's border, and close to a large street.</p>
        <p>Another bar chart highlights the most frequent words in crime descriptions from both districts. 'Cocaine' and 'rock' are predominant in Tenderloin, while Central exhibits higher occurrences of 'narcotics,' 'paraphernalia,' 'amphetamine,' and 'marijuana.' Considering Tenderloin's higher overall drug-related crimes, these word frequencies offer insights into prevalent drug types but do not necessarily indicate higher concentration compared to Central.</p>
        <p>All in all, there are large differces between drug related crimes in Tenderloin and Central district, both in terms of frequency, trends and types of drugs. These differences can be explained by historical and political factors, and hopefully, the efforts to mitigate crime will continue to lessen the drug use in both districts.</p>
    </div>
    <div class="column">
        <iframe src="/Newnewnewdrugsmap.html" height="500" width="600"></iframe>
        <br />
        <img src="https://github.com/AndersNielsen77/AndersNielsen77.github.io/blob/main/docs/assets/images/newplotnewnewnew.png?raw=true" alt="Bar chart of Tenderloin and Central" height="500" width="500">
        <iframe src="https://github.com/AndersNielsen77/AndersNielsen77.github.io/blob/main/_includes/FREQ.html" height="500" width="500"></iframe>
    </div>
    <div class="column">
        <h2>Bar chart of the yearly number of 'DRUG/NARCOTICS' crimes in Tenderloin and Central</h2>
        <p>The following bar chart shows the development of the drug/narcotic crimes in the two districts, where the number of incidents are not normalized, but shown as real numbers to convey the difference between the chosen districts. </p>
        <p> From the bar chart it appears that crimes related to drugs and narcotics are noticeably higher in Tenderloin than in Central. There is a general declining trend after this peak, which seems to further decrease after 2014. According to Wikipedia, drug crimes in Tenderloin have escalated since 2007, and parking in both sides of streets in the district was banned in early 2014 in an attempt to curb some of the narcotics crimes [1]. The decrease implies that some of the city's regulations and attempts to mitigate crime has worked, as the drug crimes in Tenderloin decrease after the law concerning parking in 2014. The peaks and decline in drug use in the Central district, however, does not match the trends seen for Tenderloin. Instead, drug use in Central peaks both in 2008 and 2014, demonstrating the difference in drug use between the two districts.  </p>
        <h2>Bar chart of the 8 most frequent words in the description of crimes across the two districts </h2>
        <p> The interactive Bokeh graph below presents the eight most frequently used words in the descriptions of drug/narcotic incidents recorded in the Tenderloin and Central districts. These words were identified by averaging the TF-IDF scores [4] from both districts. The TF-IDF algorithm was applied to the combined text from the incident descriptions in the Tenderloin and Central districts [3]. </p>
        <p>The graph indicates that 'cocaine' and 'rock' are used more frequently in the Tenderloin district descriptions, significantly more so than in the Central district. Conversely, the Central district exhibits higher frequencies of the words 'narcotics,' 'paraphernalia,' 'amphetamine,' and 'marijuana' compared to the Tenderloin. When taking into account that general drug-related crime counts are much higher in the Tenderloin compared to Central, the frequency of certain words used in crime reports does not necessarily indicate that Central has higher concentrations of those crimes. This factor should be considered when interpreting the data from the Bokeh graph. It's also reflected in the heatmap provided above, which visualizes the intensity of drug-related incidents geographically. The word data can however be used to get an indication of which type of drug crime is most apparent in a given district.</p>
    </div>
</div>



### Sources 
1. "The Tenderloin", FoundSF, accessed on 1 April 2024, https://www.foundsf.org/index.php?title=The_Tenderloin
2. "Nob Hill, San Fransisco", Wikipedia, The Free Encyclopedia, Wikimedia Foundation, 27 June 2024, https://en.wikipedia.org/wiki/Nob_Hill,_San_Francisco
3. "Tenderloin, San Fransisco", Wikipedia, The Free Encyclopedia, Wikimedia Foundation, 13 March 2024, https://en.wikipedia.org/wiki/Tenderloin,_San_Francisco
4. "tf-idf", Wikiepdia, The Free Encyclopedia, Wikimedia Foundation, 17 March 2024, https://en.wikipedia.org/wiki/Tf%E2%80%93idf


### Contributions 
**The group has worked together on all parts of the assignment. The following list shows the main contributor of each part of the assignment:** 

**s204606 - Liv**  
Bar chart Introduction and Summary 

**s194299 - Anders**  
Heat map

**s185382 - Magnus**  
Bokeh plot
