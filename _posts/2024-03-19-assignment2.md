---
layout: default
title: "02806 Assignment 2"
date: 2024-03-19 21:48:30 +0100
categories: Update
---

<link rel="stylesheet" type="text/css" href="path/to/your/css/file.css">

<div class="container">
  <div class="assignment-header">
    <h1>Assignment 2 for 02806 Social Data Analysis and Visualization</h1>
    <p>This assignment is made by students s204606, s194299, and s185382.</p>
  </div>

  <div class="assignment-section">
    <h2>Introduction to the assignment</h2>
    <p>This assignment compares the two police districts Tenderloin and Central, in northeastern San Francisco, based on the dataset SF Crime Data. The districts are specifically compared for the crime category 'DRUG/NARCOTIC', where we visualize and study the difference between these two districts in regards to the crime category over time, for weekdays, and visualize where the crimes have happened in the districts. These specific districts are compared as there is a much higher drug and general crime activity in Tenderloin than in Central, despite Tenderloin being much smaller in size, and the districts bordering each other. Historically, Tenderloin has been a very poor neighbourhood, with subsidized housing and many immigrants moving to the area. In contrast, the Central district includes areas like Nob Hill, North Beach, and the Financial District, all wealthy areas with luxury hotels and restaurants frequently visited by tourists.</p>
  </div>

  <div class="assignment-section">
    <h2>Bar chart of the yearly number of 'DRUG/NARCOTICS' crimes in Tenderloin and Central</h2>
    <p>The following bar chart shows the development of the drug/narcotic crimes in the two districts, where the number of incidents are not normalized, but shown as real numbers to convey the difference between the chosen districts.</p>
    <img src="https://github.com/AndersNielsen77/AndersNielsen77.github.io/blob/main/docs/assets/images/newplotnewnewnew.png?raw=true" alt="Bar chart of Tenderloin and Central">
  </div>

  <div class="assignment-section">
    <h2>Map plot of the incidents of drug/narcotics crimes</h2>
    <p>The next visualization shows the coordinates for incidents of drug use, where higher concentrations of incidents are represented by a red color.</p>
    <iframe src="/Newnewnewdrugsmap.html" height="500" width="700"></iframe>
  </div>

  <div class="assignment-section">
    <h2>Bar chart of the 8 most frequent words in the description of crimes across the two districts</h2>
    <p>The interactive Bokeh graph below presents the eight most frequently used words in the descriptions of drug/narcotic incidents recorded in the Tenderloin and Central districts.</p>
    {% include FREQ.html %}
  </div>

  <div class="assignment-summary">
    <h2>Summary</h2>
    <p>This assignment analyzes crime data from two police districts, Tenderloin and Central, in northeastern San Francisco, focusing on the 'DRUG/NARCOTIC' category. Despite Tenderloin's smaller size, it exhibits significantly higher drug-related crime rates than Central.</p>
  </div>

  <div class="assignment-footer">
    <h2>Sources</h2>
    <ul>
      <li>"The Tenderloin", FoundSF, accessed on 1 April 2024, <a href="https://www.foundsf.org/index.php?title=The_Tenderloin">https://www.foundsf.org/index.php?title=The_Tenderloin</a></li>
      <li>"Nob Hill, San Francisco", Wikipedia, The Free Encyclopedia, Wikimedia Foundation, 27 June 2024, <a href="https://en.wikipedia.org/wiki/Nob_Hill,_San_Francisco">https://en.wikipedia.org/wiki/Nob_Hill,_San_Francisco</a></li>
    </ul>

    <h2>Contributions</h2>
    <p>**The group has worked together on all parts of the assignment. The following list shows the main contributor of each part of the assignment:**</p>
    <ul>
      <li>**s204606 - Liv**<br>Bar chart and summary</li>
