# IPL Data Analysis Using Apache Spark

## Project Overview
This project performs exploratory data analysis (EDA) and insights generation from Indian Premier League (IPL) datasets using Apache Spark and Python (PySpark).  
The dataset contains match-level, ball-by-ball, and player-level information.  
The focus is on leveraging big data tools to handle and analyze large-scale cricket data efficiently.  

I extended this project by adding my own queries, transformations, and insights beyond the base dataset analysis.

---

## Dataset Used
- Ball_By_Ball.csv → Ball-by-ball delivery details  
- Match.csv → Match metadata (venue, date, teams)  
- Player.csv → Player information  
- Player_match.csv → Player performance per match  
- Team.csv → Team details  

---

## Tech Stack
- Programming Languages: Python, SQL  
- Big Data Frameworks: Apache Spark (PySpark)  
- Libraries: Pandas, NumPy, Matplotlib (for some visualizations)  
- Environment: Jupyter Notebook  

---

## Key Features & Analysis
- Performed ETL (Extract → Transform → Load) on IPL datasets using PySpark  
- Cleaned and preprocessed raw data for better queries  
- Analyzed player performance, team statistics, and match outcomes  
- Computed win ratios, batting/bowling performance metrics  
- Used Spark DataFrames & SQL for large-scale joins, aggregations, and group operations  
- Added custom queries such as:  
  - Best batsmen across seasons  
  - Most consistent bowlers  
  - Teams with best chasing/defending record  
  - Venue-wise match outcome trends  

---

## Sample Insights
- Top 5 highest run scorers in IPL history  
- Bowlers with the best economy rates  
- Win percentage of teams when chasing vs defending  
- Most successful venues for home teams  

---

## How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/SAHILSHARMA057/IPL_DATA_ANALYSIS.git
   cd IPL_DATA_ANALYSIS
2. Install Requirements   
    pip install pyspark pandas matplotlib

3. Open Jupyter Notebook
    jupyter notebook IPL_DATA_ANALYSIS_SPARK.ipynb

