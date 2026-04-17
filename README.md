# SpaceX-Data-Analysis-SQL
SpaceX SQL Data Exploration
# Create README.md file
readme_content = """
# SpaceX-Data-Analysis-SQL

A SQL-based exploratory data analysis of SpaceX Falcon 9 launch records using SQLite.

---

## Project Overview
This project focuses on querying a comprehensive SpaceX dataset to extract insights regarding launch site performance, payload trends, and mission outcomes. The analysis was conducted using SQL magic commands within a Jupyter Notebook environment.

## Key Features
* **Site Analysis**: Identifying unique launch sites and filtering mission counts by location.
* **Payload Calculations**: Determining average and maximum payload mass for specific booster versions.
* **Outcome Tracking**: Ranking landing successes and failures across different timeframes and landing platforms (Drone Ship vs. Ground Pad).
* **Temporal Queries**: Filtering and extracting records based on specific dates and months using SQLite's string manipulation.

## Tools Used
* **Language**: SQL (SQLite syntax)
* **Interface**: Jupyter Notebook
* **Libraries**: `ipython-sql`, `sqlite3`, `pandas`

## Dataset Description
The analysis utilizes a CSV dataset containing:
* **Date**: Mission date.
* **Booster_Version**: Version of the Falcon 9 rocket.
* **Launch_Site**: Location of the launch.
* **Payload_Mass__KG_**: Weight of the cargo in kilograms.
* **Landing_Outcome**: Result of the first-stage landing attempt.

## How to Run
1.  Install dependencies: `pip install ipython-sql pandas`.
2.  Open the `.ipynb` notebook.
3.  Load the data into SQLite using the provided Python connection script.
4.  Execute the SQL cells to view the analysis results.
"""

with open("README.md", "w") as f:
    f.write(readme_content.strip())sudo 
