## Short Description

This repository serves as the online appendix for Evert & Klint (2019) Master Thesis-project. The project investigates how the level of education and work experience has evolved among danish electives since 1849. This repository mainly contains the code for collecting and tidying data from the Danish Parliament's open data source "Folketingets Åbne Data" and from the Danish Parliament website.. In the future, this repository will also serve as a platform to share out data and results. 


## Dependencies

The code depends solely on R, version 3.4.1. Packages to supply Base-R are installed in the code. 

## Files

The project contains the following files

### Code
1. 01_BANANA.Rmd: Collects and analyses agenda data.
2. 02_BANANA.Rmd: Collects and cleans member data from the API
3. 03_BANANA.Rmd: Collects the text resumes from the Parliament website
4. 04_BANANA.Rmd: Cleans the text resumes from the Parliament website, e.g. by merging it with the member data
5. 05_BANANA.Rmd: Analyses and visualizes how use of words differ across party lines. 
6. 06_BANANA.Rmd: A preliminary use of structural equation models to take the meta variables into account in the analysis

### Data
*Is to come*

### Results
*Is to come*

## More Information
Some of the scraper functions has been set to eval=F, as they may be outdated at one point and as we hope to apply less pressure on the Danish Parliament Website. We strongly suggest to rely mainly on the API-function. A knitted version of each of the coding files is available in the code-folder. 
