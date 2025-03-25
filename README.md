# End-to-End Sports Data Analytics – T20 World Cup Cricket Analysis
## Project Overview
This project focuses on end-to-end sports data analytics using T20 World Cup cricket data. We leverage web scraping, data preprocessing, and Power BI visualizations to analyze match results, batting & bowling performances, and player statistics. The dataset is sourced from ESPN Cricinfo via web scraping.

## Technologies Used:
- Web Scraping: JavaScript & Cheerio.js to extract match statistics from ESPN Cricinfo
- Python & Pandas: Data cleaning and preprocessing
- Power BI: Data visualization and analysis

## Project Structure
``` bash
📁 End-to-End-T20-Analytics  
│── 📜 t20_wc_match_results.js   # Web scraping match results  
│── 📜 t20_wc_batting_summary.js  # Web scraping batting stats  
│── 📜 t20_wc_bowling_summary.js  # Web scraping bowling stats  
│── 📜 t20_wc_player_info.js  # Web scraping player details  
│── 📊 t20_data_preprocessing.ipynb  # Data cleaning & transformation  
│── 📊 Stage-1.pbix  # Initial Power BI model  
│── 📊 Stage-2.pbix  # Advanced Power BI analysis  
│── 📊 Stage-3.pbix  # Final visualization dashboard

```


## Data Pipeline

### 1. Data Extraction (Web Scraping)
- Extract match results, player statistics, and team performances using JavaScript.  
- Store data in structured JSON format.  

### 2. Data Cleaning & Transformation (Python & Pandas)
- Handle missing values, standardize formats, and filter relevant features.  

### 3. Perform Exploratory Data Analysis (EDA)
- Analyze key trends and insights from the dataset.  

### 4. Data Visualization (Power BI)
- Create dashboards for team & player performances, match trends, and key insights.  

## Power BI Dashboard Highlights
- **Match Results Analysis** – Win margins, team performances.  
- **Batting Performance** – Strike rate, top scorers, dismissal types.  
- **Bowling Performance** – Economy rates, wickets taken, bowling impact.  
- **Player Insights** – Career roles, playing styles.  

## How to Run the Project

### 1. Web Scraping (JavaScript)
Run each JavaScript script in a Node.js environment to extract data from ESPN Cricinfo.  

```sh
node t20_wc_match_results.js
node t20_wc_batting_summary.js
node t20_wc_bowling_summary.js
node t20_wc_player_info.js

```

### 2. Data Preprocessing (Python)
Use Jupyter Notebook (t20_data_preprocessing.ipynb) to clean and transform the scraped data.

``` sh
jupyter notebook t20_data_preprocessing.ipynb
```

### 3. Load Data into Power BI
- Open Stage-3.pbix in Power BI.
- Refresh the dataset to update the latest cricket stats.
- Explore interactive visualizations.

## Sample Insights
Here are some key findings from our analysis:

- Highest Individual Scores: Player A scored 120*(60) in Match 3.
- Most Wickets in a Match: Player B took 5 wickets for 20 runs.
- Team with Best Win Percentage: Team Z won 80% of their matches.

![image](https://github.com/user-attachments/assets/3a85ab8d-88ae-4633-a31f-2230a4d54584)

![image](https://github.com/user-attachments/assets/27f52400-4e4e-4018-bc51-be096476acd1)


## Future Improvements
- Automate daily data updates using APIs.
- Implement machine learning models for performance prediction.
- Enhance dashboards with real-time match updates.

