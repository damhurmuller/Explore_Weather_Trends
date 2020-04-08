# Explore the Weather Trends
## by Mário Damhur

## Introduction

In this project, I will analyze local and global temperature data and compare the temperature trends where I live to overall global temperature trends.

## Dataset

The dataset was extracted from the udacity database with SQL commands.

```
SELECT *
FROM global_data;

SELECT year, avg_temp
FROM city_data
WHERE city = 'Manaus';
```

The generated files were saved in the directory `data/`. Contains two files with two features each:
- **global_temp_avg.csv**: Trend of global average temperature in each year
    - year
    - avg_temp
- **manaus_temp_avg**: Trend of average temperature of my city (Manaus - Brazil) in each year
    - year
    - avg_temp

After the wrangling process, the datasets were combined to generated one master dataset to work with.


![alt text](https://github.com/damhurmuller/Explore_Weather_Trends/blob/master/images/final.png "Title")


## Summary

- There is evidence that suggests that the global temperature is getting hotter over the years and it is possible to check this trend in local cities.

## Files

- **data**: Folder of datasets.
- **images**: Folder of images.
- **exploring_weather_trends.ipynb**: Jupyter notebook containing the wrangling data process and the insights analysis.
- **README<span>.md</span>**: This file.
- **wrangling_process.pdf**: File that communicates the wrangling data process and the analysis.

## Python Libraries Used
- **pandas**
- **matplotlib**
- **seaborn**
