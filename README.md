# Predicting Levels of Pollutants Across the United States
> Our goal is to identify and predict areas that have low levels of pollutants to help those more susceptible to pollution find a safer place to live.

## Table of Contents
* [Dataset Information](#dataset-information)
* [Technologies Used](#technologies-used)
* [Model](#models)
* [Findings](#results)
<!-- * [License](#license) -->


## Dataset Information
- Dataset is from [Kaggle](https://www.kaggle.com/datasets/alpacanonymous/us-pollution-20002021)
- Including CO, NO2, O3, and SO2 pollution data in the USA between 2000 to 2021
- This dataset has about 69k entries and 24 columns


## Technologies Used
- Databricks
- SQL
- R


## Models
List the model we built here:
- Random Forest 
- Decision Tree
- Gradient Boost
- Linear Regression
We use AUC to measure their model performance, and we found that the best model performance is Random Forest to predict O3 pollution and the best model performance to predict SO2 pollution is Gradient Boost.


## Findings
For predicting levels of O3, time of year had a large effect on the data, both the month and the year. For SO2 levels, the data showed a high correlation again with the year but also with the Eastern time zone. Thus, we can see that as the years progressed, levels of both O3 and SO2 have increased, with some further impact from the month and region of record.
