# Advanced_Data_Visualization
Choose your own assignment (Advanced data visualization)

## General information
**What is this repo for?**
This repository contains my completed Advanced Data Visualization assignment for ENVS 193DS (Winter 2026). The project analyzes personal daily data to explore patterns related to sleep, activity, and stress. The repository includes the cleaned dataset, code used to generate multiple visualizations, and the rendered HTML output of the analysis.

**Whose repo is it? Who is contributing to it?**

This is Sami Gibson’s repository. All work was completed by Sami Gibson as an individual assignment for ENVS 193DS: Environmental Data Science at UCSB (Winter 2026). The assignment instructions were provided by the course instructor.

## Data and file information
**What files are there?**
The repository is organized into several folders:

`my_code_files/`: Contains the R Markdown file I used to generate the visualizations (named: DV_code) and the rendered HTML version of the assignment. This also contains the exported visualization files produced from the code.

`data/`: Contains the personal dataset used for the analysis ("193DS data - stress (6).csv"). The dataset includes daily observations of sleep duration, sleep efficiency, stress levels, steps taken, and other lifestyle variables collected over time.

`README.md`: Provides an overview of the repository contents and instructions for accessing the rendered output.

**What code is there, and what does it do?**

The code in this repository completes the Advanced Data Visualization assignment for ENVS 193DS. The script begins with a setup chunk that loads required R packages and imports the dataset. The code then cleans and prepares the data by standardizing column names, converting dates into proper date format, creating ordered weekday factors, and transforming variables such as sleep efficiency into numeric values. Several visualizations are created using ggplot2, including: Plot 1: A boxplot with jittered points showing how sleep duration varies across days of the week, Plot 2: A binned scatter plot showing the relationship between sleep duration and sleep efficiency, Plot 3: A calendar-style heatmap that visualizes daily sleep duration over time, Plot 4: A scatter plot showing the relationship between daily steps and sleep duration, with color representing time spent stressed. The code also applies custom color palettes, fonts, and themes to create a cohesive infographic-style visualization. Additional annotations and reference lines are included in the write up section at the bottom to highlight important patterns in the data.

## Rendered output

[Link:](https://samantha-gibson05.github.io/Advanced_Data_Visualization//Code_files/my_code_files/DV_Code.html)
