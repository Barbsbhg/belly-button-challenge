# belly-button-challenge

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

       








