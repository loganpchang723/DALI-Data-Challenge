# DALI-Data-Challenge
This is my repo for the Dartmouth DALI Lab's Data Challenge

## About
As part of my application to the Dartmouth DALI Lab, I chose to do the data challenge. Using the DALI_Data-Anon data from [here](https://github.com/dali-lab/dali-challenges/tree/master/data), my idea was to do a rigorous EDA and try to build a model that could predict a respondent’s “happiness”. In this repo, I have included all the raw data files I used and created, along with jupyter notebooks of my analysis and modeling stages.

## Contents
- ***data***: contains the raw data and all created .csv files used through the process
- ***notebooks***: contains the jupyter notebooks of raw analysis and modeling. The files are numbered in order of their creation and should be read in ascending order (0-2)

## Technologies Used
- **Languages:** Python 3.7, json
- **Data Handling:** NumPy, Pandas (data handling), 
- **Visualization:** seaborn, MatPlotLib (specifically Pylot) 
- **Preprocessing:** GPLearn (GP symbolic transformer), StandardScaler (data scaling and normalization)
- **Modeling and Metrics:** SciPy (additional statistics), SciKit-Learn (modeling and metrics) 

## Usage/Viewing
Really all that’s needed is to look in the ***notebooks*** folder and follow the notebooks in sequential order. Code and commentary are in all the notebooks.

## References
GP Transformer: [GPLearn documentation](https://gplearn.readthedocs.io/en/stable/intro.html#transformer)
