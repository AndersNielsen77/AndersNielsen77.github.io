---
layout: default
#layout: single
title:  "02806 Final Assignment"
date:   2024-05-06 09:00:30 +0100
categories: Update
#classes: wide
---


# Final assignment for 02806 Social Data Analysis and Visualization
This assignment is made by students s204606, s194299 and s185382.  

### Introduction to the assignemnt 
As part of the Renewable Energy Directive in 2009, the European Union set a target that the pooled energy consumption in the EU should include 20% renewable energy by 2020. In 2018, this goal was revised to 32% by 2030, and again in 2023 to at least 42.5% at EU level by 2030. [1]
This continuous increase of the Renewable Energy directive indicates that the matter of global warming is more pressing than previously thought. This begs the question if the EU-targets have been effective in changing member countries’ energy production, and if the countries are in fact on track to reach the targets by 2030. This comparative analysis will therefore deep dive into the energy production of Denmark and Sweden, using the dataset ‘Global Electricity Production’ as the basis for analysis. This dataset includes daily data about energy production for 48 different countries, including the mode of production (solar, nuclear, wind etc), as well as imported and exported energy in GWh.  


### Global energy production over time 
To gain an initial insight into the production of energy worldwide, a map is constructed which shows the development in energy production from year 2010 to year 2021. This visual tool helps in assessing the global trend towards greener energy sources.

<iframe src="/renewable_production_over_time2.html" height="500" width="720"></iframe>

Generally, the global trend is that each country produces a higher percentage of renewable energy. Worth noting is that some countries do not have data prior to 2014, which is why China for example is only visible after this. Overall, there is a positive trend for the European countries, which is promising for reaching EU's RED. For Iceland and Norway, a high percentage og their produced energy is already renewable, and so their development is not very noticeable. For Denmark and Sweden, however, the increase in percentage of renewable energy is quite similar, and it seems that the evolution of renewable energy in the two countries follow each other closely. The different modes of energy production of Sweden and Denmark will now be invetigated in more detail.

### Production of different energy types over time

<iframe src="/combined_figure.html" height="500" width="720"></iframe>

When looking into the different types of energy, Sweden and Denmark does display a significant difference. Sweden has a rather large production of nuclear power, which Denmark does not. Currently, nuclear power is not classified as a renewable energy source, but rather a 'low-carbon' energy source by the EU. This means that the energy produced by nuclear power does not count towards the RED goal the EU has set. However, nuclear energy emits negligeable amounts of CO_2, making it a green and clean source of energy (CITE). Furthermore, energy policy expert Suriya Jayanti argues that climate change cannot be stopped without the help of nuclear power, in an article in Time Magazine (CITE). Therefore, exploring the significance of nuclear power in Sweden and Denmark is also relevant when looking at energy production and its contribution to climate change. The upside in using nuclear power, is that many renewable energy sources are dependent on weather, such as solar energy and wind energy, which is the only two renewable energy sources produced in Denmark. We will now look closer at the how the renewable energy production varies throughout the year. 


### Wind energy production in Denmakr over time 
When is it important to have nuclear power? For example when the wind production is not very high - example in 2021. 

<iframe src="/Electricity_breakdown.html" height="530" width="720"></iframe>

From the graph above, it is clear that wind production is not always consistent. In months with an excess of wind, energy is exported to nearby countries, and in times of low wind energy production, other types of energy are used (which are non renewable), or energy is imported from nearby countries (primarily from Norway and Sweden) (CITE). https://norlys.dk/inspiration/energi/hvor-meget-af-danmarks-energi-er-vedvarende/ This begs the question if the wind and solar production even matters, if fossil fuels and non renewable energy is being imported when there is no sunshine and wind? This of course depends on what percentage of the danish and swedish energy consumption is actually imported, which the graph below shows. 


### Import and export of energy in Sweden and Denmark

% Insert import export graph

It is clear that Denmark is more dependent on imported energy than Sweden is, and that the danish renewable energy types are more volatile than the swedish. This is probably because Swedens renewable energy production includes large amounts of hydro-energy, which is not seasonal in the same way that wind and solar energy is, which is the sole renewable energy production in Denmark. Adding nuclear energy on top of the more stable renewable energy production for Sweden, means that Sweden exports more energy than it imports. As previously stated, most of the imported energy in Denmark is from Sweden and Norway, which have mostly renewable energy sources, which makes the energy consumption in Denmark mostly renewable, despite its large amount of imported energy. Having gained an insight into the development of renewable energy is Sweden and Denmark,  a trend line is employed to estimate whether or not the RED EU goals will be reached in 2030, for both Sweden and Denmark. The trendline is created using a linear regression model. 


### Will we reach the RED EU target in Sweden and Denmark?
Will we reach the EU target in 2050? 

Discussion - will need to think about 


### Summary 


### Sources 
1. 'Renewable Energy Directive', _European Comission_, 3 May 2024, https://energy.ec.europa.eu/topics/renewable-energy/renewable-energy-directive-targets-and-rules/renewable-energy-directive_en
2. ‘What is nuclear energy (and why is it considered a clean energy)?’, _National Grid_, 27 Mar 2024, https://www.nationalgrid.com/stories/energy-explained/what-nuclear-energy-and-why-it-considered-clean-energy



### Contributions 
**The group has worked together on all parts of the assignment. The following list shows the main contributor of each part of the assignment:** 

**s204606 - Liv**  
Bar chart Introduction and Summary 

**s194299 - Anders**  
Heat map

**s185382 - Magnus**  
Bokeh plot
