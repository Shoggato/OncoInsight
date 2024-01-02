## OncoInsight: Mice Cancer Therapy Analytics

## Overview
OncoInsight presents a comprehensive analysis of cancer therapy drugs using a dataset of 249 mice diagnosed with Small Cell Carcinoma (SCC). Focused on identifying promising drugs—Infubinol, Ceftamin, Ramicane, and Capomulin—the analysis encompasses data processing, summary statistics, visualization, and correlation exploration.

## Project Structure
Explore OncoInsight's structured analysis:

1) __Data Processing:__
  * Dependencies and Setup: Importing essential libraries.
  * Data Collection: Reading and merging mouse metadata and study results.
  * Data Cleansing: Eliminating duplicate mouse data.
2) __Summary Statistics:__
  * Summary table detailing mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.
3) __Bar and Pie Charts:__
  * Bar Plot: Visualizing total mouse timepoints for each drug regimen.
  * Pie Plot: Illustrating the distribution of female versus male mice.
4) __Quartiles, Outliers, and Boxplots:__
  * Final tumor volume calculation and identification of potential outliers for specific regimens.
  * Box plot visualization for tumor volume distribution among treatment groups.
5) __Line and Scatter Plots:__
  * Line Plot: Tumor volume progression over time for a single mouse treated with Capomulin.
  * Scatter Plot: Correlation analysis between mouse weight and the average observed tumor volume for Capomulin.
6) __Correlation and Regression:__
  * Correlation coefficient calculation between mouse weight and average tumor volume.
  * Linear regression modeling to explore the relationship between mouse weight and tumor volume.

## Usage
Run the analysis with ease:

1) Install Dependenciess:
```bash
pip install matplotlib pandas scipy numpy
```
2) Execute the Python script or run each code block in a Jupyter notebook.

## Results
Discover potential cancer therapy candidates, spotlighting Capomulin and Ramicane. OncoInsight emphasizes minimal deviation from the overall mouse population and substantial decreases in total tumor volume. Correlations between mouse weight and tumor volume provide additional insights for future research.

## Contributor
Erika Walker
