# Ford GoBike System Data Exploration

## Overview

This project explores the **Ford GoBike System** dataset for **February 2019** using Python's data analysis and visualization libraries. The objective is to investigate rider behavior, trip characteristics, and usage patterns through exploratory data analysis (EDA) and communicate the most significant findings through a presentation.

This project was completed as part of the **Udacity Data Analyst Nanodegree**.

---

## Dataset

The dataset contains information about individual bike-sharing trips made using the Ford GoBike System in the San Francisco Bay Area during February 2019.

Each trip record includes:

- Trip duration
- Start and end timestamps
- Start and end station information
- Geographic coordinates
- User type (Subscriber or Customer)
- Rider gender
- Birth year

The original dataset contains approximately **183,000 trip records**.

---

## Project Structure

```
.
├── Part_I_exploration.ipynb          # Exploratory Data Analysis
├── Part_I_exploration.html           # Exported HTML/PDF
├── Part_II_presentation.ipynb        # Presentation Notebook
├── Part_II_presentation.html         # Exported HTML/PDF
├── 201902-fordgobike-tripdata.csv    # Dataset
└── README.md
```

---

## Technologies Used

- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning

The following preprocessing steps were performed before analysis:

- Converted timestamps into datetime format.
- Extracted hour of day and day of week from trip start times.
- Calculated rider age using birth year.
- Removed unrealistic rider ages (below 18 and above 80 years).
- Applied logarithmic transformation to trip duration for visualization.

---

## Exploratory Analysis

The exploratory analysis consisted of three stages:

### Univariate Exploration

- Distribution of trip duration
- Distribution of user types
- Distribution of rider gender
- Rider age distribution
- Trips by hour
- Trips by weekday

### Bivariate Exploration

- Trip duration by user type
- Trip duration by gender
- Age versus trip duration
- Trips by weekday and user type
- Correlation heatmap

### Multivariate Exploration

- Trip duration by user type across gender
- Age versus trip duration by user type
- Average trip duration throughout the week by user type

---

## Key Findings

The analysis revealed several important insights:

- Most bike trips last between **5 and 20 minutes**.
- The distribution of trip duration is highly right-skewed.
- Subscribers account for the majority of rides.
- Customers generally take longer trips than Subscribers.
- Ride demand peaks during morning and evening commuting hours.
- Most riders are between **25 and 40 years old**.
- Weekday usage is considerably higher than weekend usage.
- Customer trips tend to be longer during weekends, indicating recreational use.

---

## Presentation

The presentation notebook summarizes the most important findings from the exploratory analysis using a concise set of polished visualizations.

The presentation focuses on:

1. Distribution of trip duration
2. Distribution of user types
3. Bike usage by hour
4. Trip duration by user type
5. Average trip duration throughout the week

---

## Conclusion

The Ford GoBike system is primarily used as a commuter transportation service. Subscribers dominate the user base and generally take shorter, more consistent trips during weekdays. Customers tend to take longer rides, especially during weekends, suggesting recreational usage.

---

## Author

**Vikash Kushwaha**
# Data_Analytics_with_python
