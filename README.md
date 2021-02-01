# Motivation
This is my first project for my Udacity Data Scientist Nanodegree Course. In this case my goal is to analyze a dataset applying CRISP-DM process. 

# Spain salary analysis 2008-2017

In this project you will find a quite complete analysis of the situation of salaries in Spain. You can find comparisons of salaries by states and gender, which is a topical issue. You will be able to see if the gap payment between male and females is big or small, as well as salaries of differents states. Finally we use the ARIMA model to forescast salary from 2017 onwards.

## Files in this repository
- Pictures: there are some picture of charts which were saved from the notebook
- spain_salary_distribution.csv: the dataset to analyze
- Project_1_udacity.ipynb: the notebook of the project
## Installation and packages
You will not need to install any new module. You just need to copy the following lines to import the necessary packages:
``` 
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
sns.set() # we apply the seaborn style to our charts

#To use ARIMA model to time series analysis
from statsmodels.tsa.arima.model import ARIMA
```

## Issues


## References
> [Matplotlib example charts](https://pythonspot.com/matplotlib-bar-chart/)

> [StackOverflow](https://stackoverflow.com/)

> [Machinelearningmastery.com](https://machinelearningmastery.com/time-series-forecasting-methods-in-python-cheat-sheet/)

> [Arima Model Documentation](https://www.statsmodels.org/stable/generated/statsmodels.tsa.arima.model.ARIMA.html)

> [Pandas](https://pandas.pydata.org/)

> [Numpy](https://numpy.org/)

> [Seaborn](https://seaborn.pydata.org/)

> [Kaggle](https://www.kaggle.com/)


## License

