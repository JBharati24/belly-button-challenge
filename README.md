### Belly Button Biodiversity Dashboard
This project is an interactive dashboard that explores the Belly Button Biodiversity dataset. The dataset catalogs the microbes that colonize human navels. It reveals that a small handful of microbial species (also called operational taxonomic units or OTUs) were present in more than 70% of people, while the rest were relatively rare.

## Features
Interactive Dropdown Menu: Select different samples (individuals) to explore their microbiome data.
Bar Chart: Displays the top 10 OTUs found in the selected sample. The chart updates dynamically with the sample selection.
Bubble Chart: Visualizes the full range of OTUs for the selected sample. Marker size corresponds to the sample values, and marker color represents OTU IDs.
Demographic Information: Displays the demographic metadata for each sample.
Responsive Updates: The dashboard updates all visualizations and metadata when a new sample is selected.
## Project Structure
index.html: The main HTML file that contains the structure of the webpage.
static/js/app.js: The main JavaScript file that handles loading the data and rendering the charts using D3.js and Plotly.
static/css/style.css: Optional CSS styling for the webpage.
samples.json: The dataset used for this project, hosted externally and accessed via D3.
Technologies Used
JavaScript: For scripting and interaction handling.
D3.js: For data manipulation and loading.
Plotly.js: For rendering interactive charts.
HTML/CSS: For the structure and styling of the webpage.
## Data Source
The dataset used in this project is provided by the Belly Button Biodiversity study and is loaded via a URL link to a hosted JSON file.

## How to Use
Select a Sample: Use the dropdown menu to select an individual sample.
View the Charts: The bar and bubble charts will update based on the selected sample, showing the top 10 OTUs and all OTUs, respectively.
View Metadata: The demographic information of the selected sample will display in the metadata panel.
