# Homelessness in the U.S. • Data 3320, Spring 2023
Uses data science methodology to investigate and improve our understanding of the relationship between local housing market factors and homelessness in the U.S..

## Requirements
To complete this project, Google Colaboratory is used as the main software. This is a web-based IDE for Python (programming language). Python libraries are also utilized to help clean and plot the data. GitHub is used to store the files of this project and make it easily accessible for reference when working with the data.

## Data
The project utilizes one data set [`05b_analysis_file_update.csv`](https://github.com/lbomine/Homelessness/blob/12b6714e2dd3cd70d6703a2963ea075f632d0dbc/05b_analysis_file_update.csv) and a dictionary [`HUD TO3 - 05b Analysis File - Data - Dictionary.csv`](https://github.com/lbomine/Homelessness/blob/12b6714e2dd3cd70d6703a2963ea075f632d0dbc/HUD%20TO3%20-%2005b%20Analysis%20File%20-%20Data%20-%20Dictionary.csv) describing the variables in the data set. 

The data for this project consists of various demographic, housing, and economic factors and are described in U.S. Department of Housing and Urban Development's (HUD) report [Market Predictors of Homelessness](https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf).

## Data Preparation
Used this [Data Preparation Notebook](https://github.com/lbomine/Homelessness/blob/b1a185b5087448b4b209cc828a62ec7917d305ab/Homelessness_Data_Preparation_Leiana_Omine.ipynb) to import the data sets and prepare the data.
<br> <br> Steps Taken:
- Inspected the contents of the data set and dictionary.
- Removed unnecessary parts of the data sets.
- Selected relevant subsets of the data. These are the predictors in the model.
- Renamed the columns to follow best practices of being lowercase, snake_case, and understandable.
- Identified missing values in the data sets. Imputed or removed NaN values.
- Ensured that the data frame is in a tidy, or long, format.
- Created derived variables that will be useful in the analysis.
- Exported the [clean data set](https://github.com/lbomine/Homelessness/blob/b1a185b5087448b4b209cc828a62ec7917d305ab/clean_homelessness.csv).

## Data Analysis
Used this [Analyis Notebook](https://github.com/lbomine/Homelessness/blob/6ac2a1387262174ba072c4d2d6107ca2cf685cee/Homelessness%20Analysis%20-%20Leiana%20Omine.ipynb) to analyze the cleaned data set and produce all necessary results for the final conclusion. Additional questions were proposed to assist our understanding and interpretation of the data.
<br> <br> Questions:
1. What are some of the biggest factors on homelessness?
2. Does homelessness rates change based on location?

Additional Step:
1. Does gentrification increase the rate of homelessness? And how can we identify it?

Analysis Methods:
- Train Test Split
- Multiple Linear Regression
- K-fold cross validation on Lasso, Ridge, and XGBoost Regression Models.
- Determined the effectiveness of each model and their variable importance.

A more in depth visualization of the results can be viewed in the [Communicating Results](https://github.com/lbomine/Homelessness/blob/b34a6a6f0768aab5d02fb9d33a1c0c3af1778019/Communicate%20Results%20Homelessness%20-%20Leiana%20Omine.pdf) report.

## Author
Leiana Beatriz Omine - Student at Seattle University

## License
Materials in this repository may be reused but not modified.
