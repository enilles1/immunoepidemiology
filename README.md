
**Overview**

This repository contains the code and data to replicate or build on our analyses. 

**Repository Structure**

**/data**: Contains the de-identified dataset of all study participants used for analyses.
        **cohort_df.csv**: This file includes de-identified data without personal identifiers. Dates of sample collection have been adjusted to Monday of the corresponding week. 

**/script**: Contains the R Markdown script for conducting the analysis and key figures.
        **immunoepi.Code.Rmd**: This script, developed in RStudio, contains the code for data analysis and visualization.

**To run the analysis:**

Clone this repository to your local machine.

Open the **immunoepi.Code.Rmd** file in RStudio.

Set your working directory in R to the script folder of the cloned repository.

Run script.

**To run additional analyses**

The code replicates the main figures. To generate additional figures based on different subsets of data (like the number of interval vaccine doses received), modify the **dfx** dataframe using **filter()** or other data manipulation functions. Then, rerun the relevant parts of the script.

**Citation**

Nilles et al. Non-linear kinetics of individual-level immune responses drive predictable population-level SARS-CoV-2 serological set points.
