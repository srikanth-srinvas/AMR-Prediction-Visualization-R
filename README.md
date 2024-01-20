# AMR-Prediction-Visualization-R
AMR Data Analysis &amp; Visualization in R  Explore antimicrobial resistance (AMR) data with R code for filtering, plotting distribution of samples worldwide, prevalence of species over years, and predicting resistance trends. Gain insights into AMR patterns, resistant pathogens, and future trends.
# Data Analysis and Visualization with R

This repository contains the code for our project submitted to the Vivli AMR Data Challenge titled "The ESKAPE threat: A Global Perspective on Epidemiology, Distribution, and Resistance,"
The Scripts mainly utilise the AMR R package https://github.com/msberends/AMR  

## Sorting the raw data based on requirement
- Load required libraries: dplyr, magrittr, tidyr
- Read raw data from a CSV file and filter it based on species and country
- Save the filtered data to a new CSV file
- Remove empty columns from the data and save the modified data to another CSV file

## Creating a distribution plot of samples across the world
- Load required libraries: ggplot2, maps
- Read data from a CSV file and create a world map
- Merge data with the world map and create a distribution plot using ggplot2
- Save the plot as a PNG file

## Generating a plot for prevalence of species by year
- Load required libraries: ggplot2, dplyr
- Read data from a CSV file and create a line plot to show the prevalence of species over the years
- Save the plot as a PNG file

## Preparing the data for MDR analysis using the AMR package
- Load required library: dplyr
- Read raw data from CSV file and convert entries to R, I, S format from Resistant, Intermediate, Susceptible format
- Save the updated data to a new CSV file

## Determining the MDR isolates count using the AMR package
- Load required library: AMR
- Use the `mdro()` function to determine the MDR isolates count from the prepared dataset

## Generating a plot for the MDR analysis
- Load required libraries: ggplot2, tidyverse
- Use example data to create a grouped bar plot showing MDR isolate count among total isolates for ESKAPE pathogens
- Save the plot as a PNG file

## Future antimicrobial resistance prediction using regression models
- Load required libraries: dplyr, ggplot2, AMR
- Read data from a CSV file and perform resistance prediction for a specified antibiotic
- Plot the resistance prediction results and the predicted SIR (Susceptible, Intermediate, Resistant) proportions

Feel free to use, modify, and extend the code according to your needs. Make sure to have the required libraries installed before running the code. If you encounter any issues or have questions, please feel free to create an issue or reach out to me.

Happy coding and data analysis!
