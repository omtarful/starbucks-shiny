# Healthiness of Starbucks Drinks: Nutritional Analysis

This project uses R Markdown and the `flexdashboard` package to analyze and visualize the nutritional content of Starbucks beverages. The goal is to identify healthier drink options based on nutritional data such as calories, fats, and sugars.

## Overview

The dashboard provides an interactive report to explore various aspects of Starbucks drink nutrition. It uses data extracted from the Starbucks Coffee Company Beverage Nutrition Information PDF. Additional insights are derived by comparing different types of drinks, including those based on coffee or tea, and the type of milk used.

## Data Source

The dataset is taken from the Tidy Tuesday project and includes nutritional information for all drinks available on the Starbucks menu. More details about the dataset can be found [here](https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-12-21/readme.md).

## Key Features of the Dashboard

1. **Data Exploration**: Overview of the dataset including visualization of missing values and basic statistics.
2. **Comparative Analysis**:
   - Comparison between calorie content in coffee vs. tea-based drinks.
   - Nutritional differences among drinks with different types of milk.
3. **Model Analysis**: Examination of potential linear relationships between nutritional components.

## Technologies Used

- R
- R Markdown
- Flexdashboard
- Tidyverse
- visdat
- plotly
- ggcorrplot

## Setup and Usage

### Prerequisites

Ensure you have R and RStudio installed. The following R packages are required:

```r
install.packages("flexdashboard")
install.packages("tidyverse")
install.packages("visdat")
install.packages("plotly")
install.packages("ggcorrplot")
```
