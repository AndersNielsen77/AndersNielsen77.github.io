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

<div class="container">
    <div class="column">
        <h2>Assignment 2 for 02806 Social Data Analysis and Visualization</h2>
        <p>This assignment is made by students s204606, s194299 and s185382. </p>
        <h2>Introduction to the assignment</h2>
        <p>This assignment compares the two police districts Tenderloin and Central, in north eastern San Fransisco, based on the dataset SF Crime Data. The districts are specifically compared for the crime category 'DRUG/NARCOTIC', where we visualize and study the difference between these two districts in regards to the crime category over time, for weekdays, and visualize where the crimes have happened in the districts. These specific districts are compared as there is a much higher drug and general crime activity in Tenderloin than in Central, despite Tenderloin being much smaller in size, and the districs bordering each other. Historically, Tenderloin has been a very poor neighbourhood, with subsidized housing and many immigrants moving to the area [1]. In contrast, the central district includes areas like Nob Hill, North Beach and the Financial District, all wealthy areas with luxury hotels and restaurants frequently visited by tourists [2].</p>
        <h2>Map plot of the incidents of drug/narcotics crimes</h2>
        <p> The next visualization shows the coordinates for incidents of drug use, where higher concentrations of incidents are represented by a red color. The visualization shows the change in locations for drug use from 2007 to 2017. As seen on the map above, Tenderloin district is quite consistently very concentrated with drug crimes, meaning that drug use has been reported in high volumes. When zooming in on the district, it is clear that there are no particular areas where drug use is more frequent, but all streets have dots representing places of drugs or narcotics crimes. This does not vary over the years. For the central district, the narcotics crimes are more spread out, with the streets closer to Tenderloin showing higher concentrations of crimes. There is also an area where Broadway crosses Columbus Avenue where drug crimes are more frequent, which is consistent for the whole time period. There are some bars in the area which might explain the crimes, but the more likely explanation is both these streets are quite large, and therefore probably more frequented by police, increasing the risk of being arrested. There are slight variations for the different years when looking at the concentration of drug crimes for the Central district, but nothing major. </p>
        <h2>Summary</h2>
        <p>This assignment analyzes crime data from two police districts, Tenderloin and Central, in northeastern San Francisco, focusing on the 'DRUG/NARCOTIC' category. Despite Tenderloin's smaller size, it exhibits significantly higher drug-related crime rates than Central. 
        <p>The first bar chart illustrates the yearly trends of drug/narcotic crimes, indicating higher incidents in Tenderloin. A decline post-2014 suggests effectiveness of city regulations, contrasting with Central's inconsistent trends.</p>
        <p>The map visualization depicts spatial distribution of drug crimes from 2007 to 2017. Tenderloin consistently shows concentrated drug-related incidents, whereas Central's incidents are more dispersed, with notable concentrations near Tenderloin's border, and close to a large street.</p>
        <p>Another bar chart highlights the most frequent words in crime descriptions from both districts. 'Cocaine' and 'rock' are predominant in Tenderloin, while Central exhibits higher occurrences of 'narcotics,' 'paraphernalia,' 'amphetamine,' and 'marijuana.' Considering Tenderloin's higher overall drug-related crimes, these word frequencies offer insights into prevalent drug types but do not necessarily indicate higher concentration compared to Central.</p>
        <p>All in all, there are large differces between drug related crimes in Tenderloin and Central district, both in terms of frequency, trends and types of drugs. These differences can be explained by historical and political factors, and hopefully, the efforts to mitigate crime will continue to lessen the drug use in both districts.</p>
    </div>
    <div class="column">
        <iframe src="/Newnewnewdrugsmap.html" height="500" width="600"></iframe>
    </div>
    <div class="column">
        <h2>Bar chart of the yearly number of 'DRUG/NARCOTICS' crimes in Tenderloin and Central</h2>
        <p>The following bar chart shows the development of the drug/narcotic crimes in the two districts, where the number of incidents are not normalized, but shown as real numbers to convey the difference between the chosen districts.   </p>
    </div>
</div>

{% include FREQ.html %}