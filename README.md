# R Project: Telecom Churn Analysis

## Overview
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

## Getting Started
### Prerequisites:
Ensure the necessary R packages are installed using the following commands:

```R
install.packages("shiny")
install.packages("dplyr")
install.packages("plotly")
install.packages("shinythemes")
```
### Installation:
1. Clone the repository:
```bash
git clone https://github.com/Vaishnavi18s/telecom-churn-analysis-shiny.git
cd telecom-churn-analysis-shiny
```
2. Run the Shiny app:
```R
library(shiny)
runApp("path/to/telecom-churn-analysis-shiny")
```
Replace "path/to/telecom-churn-analysis-shiny" with the actual path to the cloned repository.
### Usage
1. Load your telecom customer churn dataset in CSV format. Update the path in the read.csv 
   function in the app.R file.
   ```R
   data <- read.csv("path/to/your/dataset.csv")
   ```
2. Run the Shiny app using the instructions provided in the Installation section.
3. Explore different tabs and plots to analyze customer churn based on selected variables.
### Features
- __Bar Chart:__ Visualize the distribution of customer churn based on selected variables.
- __3D Scatter Plot:__ Explore the relationship between three selected variables in a 3D scatter plot.
- __Clustered Bar Chart:__ Compare the distribution of customer churn across different categories.
- __Heatmap:__ Analyze the density of customer churn based on two selected variables.
- __Line Chart:__ Understand the trend of customer churn over a selected variable.
- __Scatter Plot:__ Visualize the relationship between two selected variables.
  
## Screen Shots:
![IMG-20240308-WA0062](https://github.com/Vaishnavi18s/Churn-Data-Analysis/blob/main/IMG-20240308-WA0062.jpg)
![IMG-20240308-WA0063](https://github.com/Vaishnavi18s/Churn-Data-Analysis/blob/main/IMG-20240308-WA0063.jpg)
![IMG-20240308-WA0064](https://github.com/Vaishnavi18s/Churn-Data-Analysis/blob/main/IMG-20240308-WA0064.jpg)
![IMG-20240308-WA0065](https://github.com/Vaishnavi18s/Churn-Data-Analysis/blob/main/IMG-20240308-WA0065.jpg)
![IMG-20240308-WA0066](https://github.com/Vaishnavi18s/Churn-Data-Analysis/blob/main/IMG-20240308-WA0066.jpg)
![WhatsApp Image 2024-03-08 at 23.49.01_bb3f8c96](https://github.com/Vaishnavi18s/Churn-Data-Analysis/blob/main/WhatsApp%20Image%202024-03-08%20at%2023.49.01_bb3f8c96.jpg)
![WhatsApp Image 2024-03-08 at 23.49.56_4b43417e](https://github.com/Vaishnavi18s/Churn-Data-Analysis/blob/main/WhatsApp%20Image%202024-03-08%20at%2023.49.56_4b43417e.jpg)
## Contributors
-[Vaishnavi Sharma](https://github.com/Vaishnavi18s)


