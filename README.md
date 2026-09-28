# Netflix Exploratory Data Analysis

An exploratory analysis of the Netflix Movies and TV Shows dataset using Python. This project was completed as **Task 2** of the Data Analyst Internship at [SWYNEX Technologies](https://swynex.com) and builds on the cleaned dataset produced in Task 1.

**Quick links:** [Notebook](notebooks/SWYNEX_Task_2_Exploratory_Data_Analysis.ipynb) · [Dataset](data/netflix_titles_cleaned.csv) · [Video Walkthrough on LinkedIn](https://www.linkedin.com/posts/YOUR-POST-LINK)

## Overview

The goal of this project is to understand what the Netflix catalog looks like: what kind of content it holds, where it comes from, and how it has changed over time. The analysis covers summary statistics, trends and visualizations, and ends with a set of key findings.

## Dataset

- **Source:** Netflix Movies and TV Shows (public dataset), cleaned in Task 1
- **File:** [data/netflix_titles_cleaned.csv`](data/netflix_titles_cleaned.csv)
- **Size:** 8,807 rows and 12 columns
- **Columns:** show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

## Tools Used

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Jupyter Notebook](https://jupyter.org/)

## What the Analysis Covers

- Dataset structure, descriptive statistics and categorical summary
- Split between Movies and TV Shows
- Number of titles by release year
- Distribution of content ratings
- Top 10 countries and top 10 genres (records with multiple values were split before counting)
- Movie duration distribution
- Movies vs. TV Shows over time
- Number of titles added to Netflix each year

## Key Findings

1. **Movies make up most of the catalog.** There are 6,131 Movies (69.62%) and 2,676 TV Shows (30.38%).
2. **Most titles were released in the 2010s.** 2018 is the peak year with 1,147 titles.
3. **TV-MA is the most common rating**, with 3,207 titles, followed by TV-14 with 2,160. Most of the catalog is aimed at mature or teen audiences.
4. **Movie length is fairly consistent.** The average runtime is about 100 minutes and the median is 98 minutes.
5. **The United States has the most titles** (3,690), followed by India (1,046) and the United Kingdom (806).
6. **International Movies is the largest genre** (2,752 titles), ahead of Dramas (2,427) and Comedies (1,674).
7. **Additions to the platform grew quickly.** Titles added per year rose from 82 in 2015 to 2,016 in 2019.

## Repository Structure


SWYNEX-Exploratory-Data-Analysis/
├── data/
│   └── netflix_titles_cleaned.csv
├── notebooks/
│   └── SWYNEX_Task_2_Exploratory_Data_Analysis.ipynb
└── README.md


## How to Run

1. Clone the repository:

   git clone https://github.com/shaswatsingh-analytics/SWYNEX-Exploratory-Data-Analysis.git

2. Install the required libraries:

   pip install pandas matplotlib jupyter

3. Open the notebook in Jupyter:

   jupyter notebook notebooks/SWYNEX_Task_2_Exploratory_Data_Analysis.ipynb

4. In the data loading cell, set the file path to ./data/netflix_titles_cleaned.csv`, then run all cells.

## Conclusion

The analysis shows a catalog that is mostly Movies, with a large jump in content during the 2010s, a strong presence from the US and India, and a rating mix that leans toward mature audiences. These findings give a solid base for deeper analysis or a dashboard in the future.

## Author

**[Shaswat Singh]**
Data Analyst Intern, [SWYNEX Technologies](https://swynex.com)

- GitHub: [shaswatsingh-analytics](https://github.com/shaswatsingh-analytics)
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/shaswatsinghda27/)
