# EDA-Project-2
Project 2 Exploratory Data Analysis

## Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a cleaned dataset of height and weight. The dataset, initially obtained from **Project 1** (Data Cleaning), includes information such as gender, height in inches, and weight in pounds. This project aims to explore the data, identify patterns, check for outliers, and provide a foundational understanding for further analysis.

## Repository Structure

The repository is organized as follows:

```
Portfolio/
│
├── Project2_ExploratoryAnalysis/
│   ├── data/          # Contains the cleaned dataset
│   ├── scripts/       # R scripts for EDA
│   ├── results/       # HTML/PDF reports and output files
│   └── README.md      # Project description and instructions
```

### Files

- **data**: Contains the cleaned dataset used for EDA.
  - `cleaned_height_weight_data.csv`: The cleaned dataset used for analysis.
- **scripts**: R scripts used to perform EDA.
  - `eda_script.R`: The R script that performs exploratory data analysis.
- **results**: Contains the analysis results, including graphical outputs and knitted reports.
  - `eda_report.html`: The HTML report generated from the R Markdown file.
  - `eda_report.pdf`: A PDF version of the HTML report.

## Steps in This Project

1. **Load the Cleaned Data**: The cleaned dataset from **Project 1** is used for this analysis.
2. **Summary Statistics**: Basic descriptive statistics (mean, median, range, etc.) are computed to get an overview of the data.
3. **Data Visualization**: Various visualizations are created to explore the data further:
   - **Histogram**: To visualize the distribution of height.
   - **Boxplots**: To detect outliers in both height and weight.
   - **Scatter plot**: To examine the relationship between height and weight, categorized by gender.
4. **Insights and Conclusions**: The findings from the visualizations and summary statistics are discussed, highlighting important patterns or anomalies in the data.

## How to Use

To replicate this project on your machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/project-2-exploratory-data-analysis.git
   ```

2. Navigate to the `scripts/` folder and open the `eda_script.R` file in **RStudio** or your R environment.

3. Ensure you have the following R packages installed:
   ```R
   install.packages("readxl")
   install.packages("ggplot2")
   install.packages("dplyr")
   ```

4. Run the `eda_script.R` script to perform the exploratory data analysis.

5. View the knitted **HTML** or **PDF** reports in the `results/` folder to explore the findings of the EDA.

## Requirements

- **R** and **RStudio** (or other R environments)
- R packages:
  - `readxl` for reading Excel files
  - `ggplot2` for creating plots
  - `dplyr` for data manipulation

## Conclusion

The goal of this project was to clean and explore the height and weight dataset. By performing EDA, we gained insights into the data's distribution, relationships, and potential outliers. This exploration sets the foundation for more advanced analysis in future projects, such as predictive modeling.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Available Languages

This project is available in two languages:
- **English**
- **Nigerian Pidgin**
