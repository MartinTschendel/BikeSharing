# BikeSharing
Visual exploration of data from the Ford GoBike sharing system, covering the greater San Francisco Bay area. This project is conducted within a Udacity Nanodegree for Data Analytics. The data is taken from this [web page](https://www.fordgobike.com/system-data).

2019-04-11: Some interesting univariate explorations have been made (number of rides between different hours, weekdays and months)

2019-04-12: Some interesting bivariate explorations have been made

2019-04-13: Added a clustered bar chart

2019-04-14: Added a scatter plot with the geographic position of the rental stations

2019-04-15 & 16: Added information on annual ride counts to scatter plot 

2019-04-17: Polished the structure of the notebook

2019-04-20: included respective explanatory analysis documents (project_explanation_slides.ipynb & project_explanation_slides.slides.html)

2019-04-22: the plan is to use data from other cities such as New York and compare it to the data from the San Francisco Bay Area. Additionally, data such such as age could be explored 

2019-04-23: These web pages hopefully provide datasets for the purpose mentioned above:
* [bikeshare](https://www.bikeshare.com/data/)
* [Github Wiki: Bike Share Data Sstems](https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems)

2019-04-25: I will start to explore additional data on New York in this repo. These jupyter notebook files will provide the current working status: project_exploration_NY.ipynb (project_exploration_NY.html)

2019-04-26: read in and joint bike sharing data from NY

2019-04-27: Listed some data quality issues, what should be solved in the next steps

2019-04-29: Cleaned up some of the data quality issues (datetime, renamed columns, ...)

2019-04-29: Continued the cleaning up data quality issues and realized, that processing of some cells leads to MemoryErrors

2019-05-04: Due to MemoryError, I just explore NY-dataset from May 2018. All other above mentioned steps remain 

2019-05-05: described data, raised questions and created bar chart with number of rides across different times of the day

2019-05-06: creatd a bar chart with number of rides across different days of the week

2019-05-07: replaced values within column 'gender'

2019-05-10: plotted trip time of males and females in box plot "Trip Time (Seconds) of Males and Females"

2019-05-12: removed 'unknown' from box plot "Trip Time (Seconds) of Males and Females"

2019-05-13: plotted 'Trip time across different days of the week'

2019-05-14: plotted trip time of customers and subscribers in box plot "Trip Time (Seconds) between different user types"

2019-05-16: started to explore ride numbers of different user groups across different days of the week

2019-05-17: converted series to dataframe and unstacked dataframe

2019-05-18: plotted Ride Counts of Customers and Subscribers during Different Days of the Week

2019-05-19: summarized bivariate data exploration findings

2019-05-20: categorized user age of rides in different age groups

2019-05-21: plotted the number of rides grouped by 4 different user age categories

