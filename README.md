# Ford GoBike System Data
## by Abdelrahman Mohammed


## Overview
In this Project, I Perform EDA on the Ford GoBike system data.  Univariate, Bivariate and Multivariate analysis are done to study the relation between different varaibles of interset. Moreover, To communicate the results, I use *nbconvert* tool to make slide deck slides. 

## Requirements

Jupyter notebook must be installed.<br>
Python must be installed. The following python modules must be installed.<br>
```
jupyter
numpy
glob
opencv-python
matplotlib
tqdm
pytorch
PIL
```

## Dataset

Data is originally composed of 152446 rows and  13 columns. I drop 'start_station_id', 'end_station_id', 'start_lat', 'start_lng', 'end_lat', 'end_lng' since they are irrelevent to my investigation. Moreover, I drop all the null values. Thus, I am left with 84114 rows and , 7 columns. Finally I derive duration of the trip from hte start and end time of the trip and the day time from the start time and add column hour which is the hour at which the bike is rented.

## Summary of Findings

- Bikes are mostly used at Afternoon and Evening

- The distribution of the duration histogram is unimodal with the mode at 12

- The Average trip duration is higher form them than those registered members

- Despite the plot is wider for registered members (more trips), they are concentrated at less than 20 mins.

- users of docked bikes are likely to have longer trip duration than those with electric bikes

- Average trip durations of docked bikes is more than the electric ones. and the average duration of docked bikes after midnight is the largest but with high varaince

- Registered members behaviour is consistent Vs Day times. They tend to make more trips but short ones


## Key Insights for Presentation

- the day time at which the bikes are used is Afternoon, then Evening. while After midnight is the lowest

- Casual members are more likely to use the service than the registered ones (members)

- Distribution of the histogram of duration is unimodal with the mode at nearly 12 minutes!

- Registered members behaviour is consistent Vs Day times. They tend to make more trips but short ones
