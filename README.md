# Survey-Analysis
Description
# Teenage Smoking Behavior Analysis in Greater Toronto Area

This repository contains data and code for the analysis of smoking behavior among teenage ex-smokers in the Greater Toronto Area. The project involves data collection, data cleaning, exploratory data analysis, statistical inference, and hypothesis testing to understand the patterns in cigarette consumption before quitting smoking.

## Project Structure

- `data/`: Directory containing the dataset used in the analysis.
- `R/`: R scripts for data cleaning, analysis, and visualization.
- `docs/`: Documentation and any additional notes related to the project.
- `output/`: Results from the analysis including figures, tables, and statistical test results.
- `report/`: Final analysis report and any other written materials summarizing the findings.

## Data

The dataset used in this analysis simulates/surveys teenage ex-smokers' behaviors and contains information such as the number of cigarettes smoked per day before quitting and weight change after quitting, among others.

## Analysis

The analysis is performed using R and includes the following:

- Creating age categories for segmentation purposes.
- Generating boxplots to visualize the average number of cigarettes smoked per day before quitting across different age groups.
- Constructing QQ plots to check the normality assumption of the weight change variable.
- Calculating 95% confidence intervals for the mean number of cigarettes smoked before quitting.
- Conducting a hypothesis test to compare the sample mean with the national average of daily cigarette consumption.

## Results

The key findings from the analysis are documented in the `output/` directory, including a detailed report of the confidence intervals calculated and the p-values from the hypothesis tests performed.

## How to Run

Ensure you have R installed on your machine. The code is written using RMarkdown, which requires an R environment to execute. The R scripts can be run from the command line or within an IDE like RStudio.

1. Clone the repository:
git clone https://github.com/williams0822/teenage-smoking-behavior-analysis.git
2. Navigate to the `R/` directory and run the R scripts in sequence.

## Dependencies

The analysis requires the following R packages:

- `tidyverse`: For data manipulation and visualization.
- `knitr`: For output formatting.

Install them using the following commands in R:
```R
install.packages("tidyverse")
install.packages("knitr")
Bibliography
A bibliography is provided in the docs/ directory for all the references used throughout the project.

Appendix
An appendix can be found in the report/ directory, which includes additional details and data snapshots.

Contact
For any additional questions or comments, please open an issue in this repository or contact [william0822sun@gmail.com].

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
