# Aditya Pachpande's Boilerexams application Challenge
This file will contain the exploratory data analysis that I have preformed in EDA.ipynb



## Understanding the Dataset \

---
I first got some background knowledge of the dataset by looking at the dataset by querying in SQL. I also checked the data types of the columns and the number of missing values in each column.
I then looked at EDA_specific_columns.ipynb to get a better understanding of the dataset and then moved on to EDA.ipynb to perform the EDA.
I wrote some code to sample the dataset and optimised performance in Chunking_Loading.ipynb 
Then I worked in EDA.ipynb, I thought of some hypothesis and then tested them in Additional_EDA.ipynb
Finally I tried to train some XGBoost models in Ground_ML.ipynb
__
## Features

### Epoch
- **Description**: The exact time (in UTC) when the observation was made.
- **Use**: Useful for tracking time-based patterns in satellite brightness or movement.

### range_km
- **Description**: The distance from the telescope to the satellite in kilometers.
- **Use**: Helps normalize brightness data (as it directly correlates with the brightness) or identify altitude patterns of satellites.

### Mag
- **Description**: The brightness magnitude of the satellite in negative logarithms.

### Track
- **Description**: A unique identifier grouping observations that are part of the same satellite observation pass.

### epsecs
- **Description**: The time elapsed (in seconds) since the start of the current Track.
- **Use**: Useful for analyzing temporal changes during a satellite pass (variance over a short itme period).

### Satellite
- **Description**: A unique identifier for each satellite.
- **Use**: Helps indvidualise the observations made over a period.

### sat_j2000
- **Description**: The satellite’s position in the J2000 coordinate system.
- **Use**: Provides spatial information about the satellite’s position in its orbit.

### obs_j2000
- **Description**: The observer’s position in the J2000 coordinate system.
- **Use**: Helps accurately calculate the satellite’s apparent position relative to the observatory.

### az_rad
- **Description**: The azimuth of the satellite in radians, relative to the observer’s position.
- **Use**: Identifies the satellite’s position relative to the observer's horizon.

---





