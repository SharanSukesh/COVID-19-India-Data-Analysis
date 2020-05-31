# COVID-19-India-Data-Analysis
Exploratory Data Analysis of COVID-19 India Data.

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Libraries used](#libraries-used)
* [Dataset used](#dataset-used)
* [Built with](#built-on)
* [Questions answered](#questions-answered)
* [Ackowledgements](#ackowledgements)
* [Author](#author)


## About the Project 
Exploratory Data Analysis of COVID-19 India dataset to understand the spread of cases across India. </br></br>
The python notebook __"COVID-19 India Data Analysis"__ explores the current situation of the COVID-19 pandemic in India and then delves deeper into the current situation in India to answer a few questions regarding the severity of spread in different states as well as India as a whole. 

We also look into some metrics such as the death rate with respect to positive cases and rate of positive cases with respect to the number of tests. In addition we look at recovery rate and the number of tests conducted by each state to see how each state has been able to cope with the outbreak. 

### Since the graphs are implemented using plotly, they do not appear in the github preview. The notebook will need to be run using an environment like Jupyter notebook for the graphs to be visible.

## Libraries used 
* Pandas
* Numpy
* Matplotlib
* Seaborn
* plotly
* cufflinks

```bash
import pandas as pd
import plotly.graph_objs as go 
from plotly.offline import init_notebook_mode,iplot,plot
init_notebook_mode(connected=True) 
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns
import numpy as np
import cufflinks as cf
init_notebook_mode(connected=True)
# For offline use
cf.go_offline()
import os
os.environ["PROJ_LIB"] = "F:\\Downloads\\Anaconda\\Library\\share"
from mpl_toolkits.basemap import Basemap
import matplotlib.cm
from matplotlib.patches import Polygon
from matplotlib.collections import PatchCollection
from matplotlib.colors import Normalize
```

## Dataset used 
* __COVID-19 data__ - covid_19_india.csv
* __Statewise testing details__ - StatewiseTestingDetails.csv
* __Age Group Details__ - AgeGroupDetails.csv

## Built with
* Jupyter Notebook

## Questions answered 
1. How are COVID-19 cases distributed across India?
2. Which states have the highest and lowest number of cases?
3. What is the overall trend in confirmed cases, recovered patients and number of deaths?
4. How have the number of active cases changed since the first case was reported?
5. What is the state-wise distribution of deaths across India?
6. Which states have experienced the highest number of deaths thus far?
7. Which states have conducted the highest number of tests?
8. What is the state-wise rate of positive cases with respect to the total number of tests conducted?
9. What is the recovery rate in india?
10. Which states have the highest recovered percentage?
11. What is the average death rate in India and how has it fluctuated over time?
12. What is the age group distribution of cases?

## Ackowledgements
* <a href='https://www.kaggle.com/sudalairajkumar/covid19-in-india'>COVID-19 in India</a> - All datasets used in this notebook

## Author - Sharan Sukesh
