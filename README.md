# belly-button-challenge

## Table of Contents
* [Background](#background)
* [Instructions](#instructions)
* [Advanced Challenge Assignment](#advanced-challenge-assignment)
* [Hints](#hints)

Link to the dashboard: https://barbsbhg.github.io/belly-button-challenge/

## Background
In this assignment, you will build an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.  
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Instructions
Complete the following steps:
  1. Use the D3 library to read in <code>samples.json</code> from the URL <code>https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.</code>
  2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
     * Use <code>sample_values</code> as the values for the bar chart.
     * Use <code>otu_ids</code> as the labels for the bar chart.
     * Use <code>otu_labels</code> as the hovertext for the chart.
    
       ![Top 10 OTUs](Images/top%2010%20OTUs.jpeg)

  3. Create a bubble chart that displays each sample.
     * Use <code>otu_ids</code> for the x values.
     * Use <code>sample_values</code> for the y values.
     * Use <code>sample_values</code> for the marker size.
     * Use <code>otu_ids</code> for the marker colors.
     * Use <code>otu_labels</code> for the text values.  

      ![Bubble Chart](Images/bubble_chart.jpg)

  4. Display the sample metadata, i.e., an individual's demographic information.
  5. Display each key-value pair from the metadata JSON object somewhere on the page.

     ![Demographic Info](Images/demographic%20info.jpeg)

  6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

  ![Dashboard](Images/dashboard.jpeg)

  7. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file


## Advanced Challenge Assignment

The following task is advanced and therefore optional.
  * Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to plot the weekly washing frequency of the individual.
  * You will need to modify the example gauge code to account for values ranging from 0 through 9.
  * Update the chart whenever a new sample is selected.


 ![Gauge](Images/gauge.jpg)

## Hints
  * Use <code>console.log</code> inside of your JavaScript code to see what your data looks like at each step.
  * Refer to the [Plotly.js documentationLinks](https://plotly.com/javascript/) when building the plots.















