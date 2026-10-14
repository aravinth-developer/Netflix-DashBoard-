# Netflix Data Analysis Dashboard

An interactive Power BI dashboard analyzing Netflix movies and TV shows by rating, genre, country, type, and release year.

![Dashboard Preview](images/dashboard.png)

## Objective
Explore Netflix's content library to understand what type of content it offers, where it comes from, and how it has grown over time.

## Dataset
- Source: Netflix Titles dataset (<Kaggle [link](https://www.kaggle.com/datasets/shiva...)>)
- Fields: title, type, director, country, date added, release year, rating, duration, genres

## Tools Used
- Power BI (dashboard and DAX measures)
- Excel / Power Query (data cleaning)

## Dashboard Features
- **KPI cards:** Total Shows, Genres, Directors, Start and End Year
- **Rating by Total Shows:** distribution of maturity ratings
- **Genre by Total Shows:** most common genres
- **Total Shows by Country:** map view of content origin
- **Movies vs TV Shows:** content type split
- **Shows by Release Year:** trend over time, split by type

## Key Insights
- TV-MA is the most common rating, followed by TV-14.
- Dramas, Documentaries, and Stand-Up Comedy are among the top genres.
- Content releases peaked around 2018-2020.
- Movies make up a larger share than TV shows. <verify with your data>

## Repository Structure
```
netflix-dashboard/
├── data/            # Raw and cleaned dataset
├── images/          # Dashboard screenshots
├── netflix.pbix     # Power BI file
└── README.md
```

## How to Use
1. Download `netflix.pbix`
2. Open it in Power BI Desktop
3. Use the slicers and charts to explore

## Author
Srinivasa Aravinth M
Aspiring Data Analyst | Excel, SQL, Python, Power BI
[LinkedIn](linkedin.com/in/srinivasaaravinth) | [GitHub](github.com/aravinth-developer)
