# IPL 2024 RCB vs DC Analysis

This project provides a **data analysis and visualization** of the IPL 2024 match between **Royal Challengers Bangalore (RCB)** and **Delhi Capitals (DC)**. The analysis uses data from the match to explore **runs per over**, **top scorers**, and other key insights that can help understand the performance of both teams.

## Project Overview

In this analysis, the following aspects were explored:
- **Run Distribution**: Distribution of runs per over for both teams.
- **Top Scorers**: Analysis of the top players contributing to the teams' total runs.
- **Match Performance**: Insights into various match metrics like scoring consistency and player performance.

## Files Structure

- **`data/`**: This directory contains the data files, such as `innings_deliveries.csv`, which are used for analysis.
- **`notebooks/`**: This directory contains the Jupyter notebook files (e.g., `rcb_vs_dc_analysis.ipynb`) where the analysis is performed.
- **`images/`**: This directory holds saved images or visualizations that are generated during the analysis (e.g., `plot1.png`).
- **`requirements.txt`**: A file that lists the necessary Python libraries needed to run the project.
- **`README.md`**: The file that contains the project description, setup instructions, and how to use the project.

### Data

The data used for this analysis comes from the IPL 2024 match between RCB and DC. It contains information about each delivery in the match, including runs, batsmen, bowler, and more.

- **innings_deliveries.csv**: Contains details of the deliveries in the match, such as runs scored, batsman name, bowler name, and team information.

### Notebook

The analysis is implemented in a **Jupyter Notebook** located in the `notebooks/` directory. This notebook includes:

1. **Loading and Cleaning Data**: Importing and preparing the dataset for analysis.
2. **Data Analysis**: Visualizations and statistical analysis of the IPL match data.
3. **Visualization**: Various plots showing the run distribution, top scorers, and other insights.

### Requirements

To run this project locally, you need to install the dependencies listed in the `requirements.txt` file:

```bash
pip install -r requirements.txt
