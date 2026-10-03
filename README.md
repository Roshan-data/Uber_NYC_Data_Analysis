\# Uber NYC Data Analysis



\## Project Overview



This project analyzes Uber trip activity in New York City using Python and exploratory data analysis.



The objective is to identify demand patterns across time, day of week, Uber base, and geographic pickup locations.



\## Business Objective



The analysis focuses on understanding:



\- Monthly trip trends

\- Hourly demand patterns

\- Day-of-week activity

\- Day and hour demand patterns

\- Uber base distribution

\- Geographic pickup patterns

\- Pickup density across NYC



\## Dataset



The analysis uses Uber NYC trip data from April to September 2014.



The dataset contains:



\- Date/Time

\- Latitude

\- Longitude

\- Uber Base



The raw dataset is not included in this repository because of its large size.



\## Data Cleaning



The following preprocessing steps were performed:



\- Checked for missing values

\- Converted Date/Time into datetime format

\- Identified and removed duplicate records

\- Created time-based features such as month, day, hour, and day of week



After removing 82,581 duplicate records, the final dataset contained approximately 4.45 million trip records.



\## Tools Used



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Jupyter Notebook



\## Analysis Performed



\### 1. Monthly Trip Analysis



Analyzed how recorded Uber trip activity changed from April to September 2014.



\### 2. Hourly Trip Analysis



Identified the hours with the highest recorded trip activity.



\### 3. Day-of-Week Analysis



Compared Uber trip activity across the seven days of the week.



\### 4. Day × Hour Analysis



Used a heatmap to understand how trip activity varies across both day and hour.



\### 5. Uber Base Analysis



Compared trip activity across different Uber bases.



\### 6. Geographic Analysis



Visualized pickup locations and identified areas with higher concentrations of recorded trips.



\## Key Findings



\- 4.45 million trip records were analyzed after duplicate removal.

\- September recorded the highest monthly trip volume.

\- 5 PM recorded the highest hourly trip volume.

\- Thursday recorded the highest daily trip volume.

\- Pickup activity was concentrated in specific geographic areas.

\- Trip activity varied across Uber bases.



\## Business Recommendations



\- Use historical demand patterns to support driver availability planning.

\- Consider hourly and daily demand patterns when planning operational resources.

\- Use geographic demand concentration to support local driver allocation.

\- Monitor differences in activity across Uber bases.



\## Project Structure



```text

Uber-NYC-Data-Analysis/

│

├── Uber\_NYC\_Data\_Analysis.ipynb

├── README.md

├── requirements.txt

├── .gitignore

│

└── visuals/

&#x20;   ├── monthly\_trips.png

&#x20;   ├── hourly\_trips.png

&#x20;   ├── day\_of\_week\_trips.png

&#x20;   ├── day\_hour\_heatmap.png

&#x20;   ├── base\_analysis.png

&#x20;   ├── pickup\_locations.png

&#x20;   └── pickup\_density.png

