# R Project: Telecom Churn Analysis Shiny App

## Overview:
Telecom Churn Analysis is crucial for telecommunications companies to understand and predict customer behavior. This Shiny app provides an interactive platform for visualizing and analyzing customer churn within the telecom industry. Leveraging the `shiny`, `dplyr`, and `plotly` packages, the app offers an engaging user interface for exploring relationships between different variables and understanding their impact on customer churn.
## Dependencies

Make sure you have the following R packages installed before running the application:

- shiny
- dplyr
- plotly
- shinythemes
- rgl
- rpart
- shinyjs

## Getting Started:
### Prerequisites:
Ensure the necessary R packages are installed using the following commands:

```R
install.packages("shiny")
install.packages("dplyr")
install.packages("plotly")
install.packages("shinythemes")
```
## Clone the repository
git clone https://github.com/Vaishnavi18s/telecom-churn-analysis-shiny.git
cd telecom-churn-analysis-shiny

# Run the Shiny app
library(shiny)
runApp("path/to/telecom-churn-analysis-shiny")

Replace "path/to/telecom-churn-analysis-shiny" with the actual path to the cloned repository.

## Screen Shots:
## Data Source

The project uses Zomato restaurant data, which is loaded from a CSV file. Ensure that the CSV file (`data.csv`) is available at the specified location in the code. The data is cleaned and processed to prepare it for visualization.

# Load your telecom customer churn dataset in CSV format. 
# Update the path in the read.csv function in the app.R file.

data <- read.csv("path/to/your/dataset.csv")

# Run the Shiny app using the instructions provided in the Installation section.

# Explore different tabs and plots to analyze customer churn based on selected variables.

## Features

### Bar Chart: 
Visualize the distribution of customer churn based on selected variables.

### 3D Scatter Plot: 
Explore the relationship between three selected variables in a 3D scatter plot.

### Clustered Bar Chart: 
Compare the distribution of customer churn across different categories.

### Heatmap: 
Analyze the density of customer churn based on two selected variables.

### Line Chart: 
Understand the trend of customer churn over a selected variable.

### Scatter Plot: 
Visualize the relationship between two selected variables.
