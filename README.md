Data and code for SARS-COV-2 immune dynamics

**Overview**

This repository contains the code and data to replicate or build on out analyses.

**Repository Structure**
/data: Contains the de-identified, limited dataset used for analyses.
        cohort_df.csv: This file includes de-identified data without personal identifiers, ensuring participant privacy and data security.
/script: Houses the R Markdown script for conducting the analysis.
        immunoepi.Code.Rmd: This script, developed in RStudio, contains the code for data analysis and visualization.

**To run the analysis:**

Clone this repository to your local machine.
Open the immunoepi.Code.Rmd file in RStudio.
Set your working directory in R to the script folder of the cloned repository.
Run the script. It will automatically load data from the data/cohort_df.csv file.

**Data Description**

The cohort_df.csv file in the /data folder contains a full, de-identified dataset, without personal identifiers to ensure the confidentiality of the participants. The dataset is structured to support the immunological analysis outlined in the immunoepi.Code.Rmd script.

**Citation**

Nilles et al. Non-linear kinetics of individual-level immune responses drive predictable population-level SARS-CoV-2 serological set points.
