# UWMadison_CS540_Su20_P04
Assignment Webpage: http://pages.cs.wisc.edu/~yw/CS540P4S20E.htm
Repository for the 4th programming assignment of UW-Madison CS540 Summer 2020 course (Introduction to Artificial Intelligence)


## Goals
**Part 1**: Estimate parametric model describing the trend (Allowed to use package)
**Part 2**: Hierarchical clustering and K-means clustering


## Dataset
COVID-19 global deaths dataset from Johns Hopkins University: [link](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)  
*For this assignment, I retrieve data at Aug. 17, 2020 23:50 (UTC)*

### Data Preprocessing
- Combine the rows for the same country (e.g. US and Canada / data is reported by state)


## Tasks
- Data pre-processing
  - Related Question: Q1, Q2
- Fit Parametric Model
  - Related Question: Q3
- Hierarchical Clustering (Single Linkage and Complete Linkage)
- K means clustering

### Key Ideas of Implementation


## Questions
- **Q1**  
  (`original`) Enter the cumulative time series for the US and Canada (remember to add up the numbers from each state or province) (two lines, each line containing integers, comma separated).
- **Q2**  
  (`difference`) Enter the differenced time series for the US and Canada (compute the difference between consecutive numbers in the previous question, here, this time series represents the number of additional deaths each day) (two lines, each line containing integers, one less than the number of integers per line in the previous question, comma separated).
- **Q3**  
  Briefly explain the method you use to obtain the parameters. (Auto-grade will assign 5/5 for anything you enter, but I will go through them manually after the final exam to check if it is something trivial.)