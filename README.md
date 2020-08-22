![Belly-Button-BioDiversity](https://pbs.twimg.com/media/B-iLI1BCUAA_5m6.jpg:large)
# Plotly-challenge
### Belly Button Biodiversity - Coolest study of microbes that colonize human navels
In this assignment, I have built an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
### Plotly
* Data file is available as `samples.json`. The dashboard is created with the following elements..
* A horizontal bar chart that displays the top 10 OTUs found in that individual 
  * `sample_values` are values for the bar chart.
  * `otu_ids` are the labels for the bar chart.
  * `otu_labels` are the hovertext for the chart.
* A bubble chart that displays for each individual 
  * `sample_values` are the y values.
  * `otu_ids` are the x values.
  * `otu_labels` are the values for the text.
* A gauge chart that displays for the individual 
  * `weekly washing frequency` ranging from 0-9.
* Displays the sample metadata, i.e. an individual's demographic information 
  * Each key-value pair from the sample metadata
* Updates all the plots any time a new sample is selected 

