---
layout: default
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
    </div>
    <div class="column">
        <iframe src="/Newnewnewdrugsmap.html" height="500" width="600"></iframe>
    </div>
    <div class="column">
        <h2>Bar chart of the yearly number of 'DRUG/NARCOTICS' crimes in Tenderloin and Central</h2>
        <p>The following bar chart shows the development of the drug/narcotic crimes in the two districts, where the number of incidents are not normalized, but shown as real numbers to convey the difference between the chosen districts. </p>
    </div>
</div>

{% include FREQ.html %}