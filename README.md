# Analysis-of-Music-Streaming-Behaviour-Across-Cities
Analyses online music streaming data to compare user listening behaviour across cities and weekdays using data preprocessing and exploratory analysis.

## Project Overview
This project analyses real online music streaming data to explore user listening behaviour in two cities: **Springfield** and **Shelbyville**.  
The objective is to understand how user activity varies by **city** and **day of the week**, following a structured data analytics workflow.

The project covers data exploration, preprocessing, and analytical comparison, with a strong focus on data quality and clear interpretation of results.

---

## Business Objective
The main objectives of this project are to:
- Explore and understand music streaming usage patterns
- Identify differences in listening activity between cities
- Analyse how user behaviour changes across weekdays
- Demonstrate a structured, end-to-end data analysis process

---

## Dataset Description
The dataset contains real online music streaming records and is stored in:

/datasets/music_project_en.csv


### Data Dictionary

| Column | Description |
|------|-------------|
| `userID` | Unique user identifier |
| `Track` | Song title |
| `artist` | Artist name |
| `genre` | Music genre |
| `City` | User city (Springfield or Shelbyville) |
| `time` | Time of playback (HH:MM:SS) |
| `Day` | Day of the week |

---

## Project Structure
The analysis is organised into three main stages:

### Stage 1 — Data Overview
- Load the dataset
- Review structure, column names, and data types
- Perform initial data inspection and observations

### Stage 2 — Data Preprocessing
- Standardise column names
- Identify and remove duplicate records
- Handle missing values
- Prepare a clean dataset for analysis

### Stage 3 — Analysis
- Compare listening activity by city
- Analyse listening behaviour by day of the week
- Interpret results and test analytical statements
- Summarise insights in a final conclusions section

---

## Key Findings
- Listening activity varies by **day of the week**.
- Differences in user activity are observed between **Springfield** and **Shelbyville** on specific days.
- Clean and structured data is essential for producing reliable analytical comparisons.

*(Detailed results and interpretations are documented in the notebook.)*

---

## Tools & Technologies
- Python  
- Jupyter Notebook  
- pandas  
- Exploratory data analysis techniques  

---

## Repository Structure
music-streaming-user-behaviour-analysis/
├── notebooks/ # Jupyter notebook with full analysis
├── data/ # Dataset (or reference to platform dataset)
└── README.md


---

## Conclusion
This project demonstrates a complete analytical workflow, from raw data exploration to structured analysis and interpretation.  
The results highlight how user behaviour can differ across locations and time, providing a foundation for further behavioural or recommendation-based analysis.

---

## Author
**Erika González**  
MBA | Marketing & Data Analytics  
Focus areas: Data Analysis, Marketing Intelligence, Customer Behaviour
