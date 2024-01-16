![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![GitHub last commit](https://img.shields.io/github/last-commit/honghaipv/BixiDataAnalysis)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
# BIXI Data Analyses in R

A series of data analyses for BIXI open data in R, including EDA, predictive analysis, and more.




## Data
BIXI is a public bicycle-sharing system serving the areas of Montreal metropolitan with more than 10,000 bikes (including 2,600 electric bikes) and 830 stations. The data used in this project were directly downloaded from [BIXI open data website](https://bixi.com/en/open-data/).

Here is the list of used data and their last updated time:

| Name                       | Last updated |
| -------------------------- | ------------ |
| DonneesOuvertes2023_10.zip | Nov 23 12:44 |
| DonneesOuverte2022.zip     | Nov 22 15:54 |
| Historique-BIXI-2021.zip   | Nov 23 12:50 |
| Historique-BIXI-2020.zip   | Nov 23 11:25 |
| Historique-BIXI-2019.zip   | Nov 23 12:50 |


## Contents
This repository contains a series of data analysis works written in R markdown. The contents are written as reproducible step-by-step documents. The most recently updated analyses are listed as follows:

1. **01-pre-process.Rmd**: Extract, clean, and pre-process the original data into CSV files.
2. **02-demand-forecast.Rmd**: Explore data using plots, analyze the network utilization and forecast future demand using linear regression models.

The HTML outputs are knitted using R Studio and can be located in the [html](html/) folder.
## Authors

[@honghaipv](https://www.github.com/honghaipv)

Contact: honghaipvu (at) gmail (dot) com


## License
[MIT](https://choosealicense.com/licenses/mit/)
