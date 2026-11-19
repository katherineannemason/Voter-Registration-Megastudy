# Voter-Registration-Megastudy

This repository corresponds to the paper, "A Megastudy of Behavioral Interventions to Increase Voter Registration Ahead of the 2024 U.S. Presidential Election."

All cleaning and analysis code is provided. The data cannot be shared publicly because of participant identifiability concerns and IRB restrictions. Should other researchers be interested in utilizing the data, they must obtain a) ethics approval from their institution’s IRB, and b) data-use agreements with Stanford University and Murmuration.

For these reasons, we have provided simulated datasets (VR_Simulated_Data.csv and VR_Simulated_Data_Standard.csv) to demonstrate the code’s functionality. Note that the results of analyses conducted using the simulated data will differ from those reported in the main paper and supplementary materials.

Data cleaning and analyses were conducted in R v4.5, and plots were created in Python v2.5.0. Note that the code may not run properly if other versions of R and Python are used. The code has been tested on macOS Sonoma 14.4.1. and macOS Sequoia 15.7.2.

The typical time required to download this code is minimal, given that R and Python are already installed. Expected run time for all analyses is under 10 minutes on a standard desktop or laptop computer. 

# Code Files: 

Run the scripts in sequential order:

0. VR_Helper_Functions.rmd - Contains all functions written and used for data cleaning and analysis. To be run before code in the following files.  

01. VR_Data_Cleaning.rmd - Data cleaning file, deidentified. 

02. Simulated_Data_Code.rmd - Code producing the simulated data set.

03. Simulated_Data.csv - Simulated data to demonstrate code functionality.

04. Simulated_Data_Standard.csv - Simulated data to demonstrate code functionality, with standardized variables.

05. VR_Analyses_Descriptives_Corrs.rmd - Code for descriptives and 0-order correlations.

06. VR_Analyses_Primary_DVs.rmd - Code for analyses involving primary variables (link clicks, voting intentions, registration, voting).

07. VR_Analyses_Psych_DVs.rmd - Code for analyses involving additional psychological variables (trust, efficacy, norms).

08. VR_Analyses_Mediations.rmd - Code for analyses involving mediation analyses.

09. VR_Analyses_Other.rmd - Additional miscellaneous analyses.

10. VR_Analyses_Attrition Final.rmd - Code for attrition related analyses and robustness checks.

11. VR_PointPlots.ipynb - Plots in Python.

