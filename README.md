# Belly Button Biodiversity Dashboard
## Background
In this project, we will create an interactive dashboard to explore the Belly Button Biodiversity dataset. This dataset catalogs the microbes that colonize human navels. It reveals that a small handful of microbial species (operational taxonomic units, or OTUs) were present in more than 70% of people, while the rest were relatively rare.

## Instructions
### Step 1: Load Data
- Use the D3 library to read in samples.json from the URL: samples.json.
### Step 2: Create a Horizontal Bar Chart
- Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in each individual.
- Use sample_values as the values for the bar chart.
- Use otu_ids as the labels for the bar chart.
- Use otu_labels as the hovertext for the chart.
### Step 3: Create a Bubble Chart
- Create a bubble chart that displays each sample.
- Use otu_ids for the x values.
- Use sample_values for the y values.
- Use sample_values for the marker size.
- Use otu_ids for the marker colors.
- Use otu_labels for the text values.
### Step 4: Display Metadata
- Display the sample's metadata, i.e., an individual's demographic information.
- Loop through each key-value pair from the metadata JSON object and create a text string.
- Append an HTML tag with that text to the #sample-metadata panel.
### Step 5: Update Plots
- Update all the plots when a new sample is selected.
### Step 6: Deploy Your App
- Deploy the app to a free static page hosting service, such as GitHub Pages.


## Usage
- Clone the repository:

## Dependencies
- D3.js
- Plotly.js


