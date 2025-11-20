# leveling-up-with-data
Data 101 final — Video game sales analysis


##Project Overview
This project analyzes historical video game sales to identify trends in platforms, genres, and regional performance. 


##Dataset Documentation


**Dataset Name:**vgsales.csv
**Source:** [Kaggle Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales)
**Last Updated:** 2025


**Description:** 
This dataset contains historical sales data for video games worldwide, including multpile platforms, genres, and regions. Each row represents a single game release. 


**Columns:** 
- **Rank:** Sales rank of the game
- **Name:** Game title 
- **Plateform:** Gaming platform
- **Year:** Release year
- **Genre:** Game genre
- **Publisher:** Company releasing the game
- **NA_Sales:** North America sales (millions)
-**EU_Sales:** Europe sales (millions)
- **JP_Sales:** Japan sales (millions)
-**Other_Sales:** Other regions sales (millions)
- **Global_Sales:** Total worldwide sales (millions)


**Limitations / Considerations:** 
-Missing release years or publisher info for some games
-Regional biases (NA, EU, JP)
-Duplicate titles across platforms treated as separate entries


## Analysis & Visualizations
The dataset was analyzed to uncover trends in video game sales across years, genres, platforms, and regions. The analysis highlights clear trends in video game sales: certain genres and platforms dominate globally, regional markets differ in preferences, and a few standout titles drive large sales spikes. These insights can inform market strategy, platform targeting, and academic research into industry trends. 

## References
1. Kaggle. "Video Game Sales Dataset." Accessed 2025.
2. Python Libraries: Pandas, Matplotlib, Numpy