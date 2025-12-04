# Table of Contents
- [Project Overview](#project-overview)
- [Visualizations and Insights](#visualizations-and-insights)
- [Dashboard Screenshot](#dashboard-screenshot)
- [Folder Structure](#folder-structure)
- [Future Improvements](#future-improvements)

---

# Project Overview
-The objective of this project is to analyze Airbnb listing data to understand pricing patterns, host performance,
property characteristics, and geographic distribution within Seattle. The analysis is designed for stakeholders such as property owners, 
potential Airbnb hosts, market analysts, and decision-makers seeking insights into rental demand and pricing trends.

-Key business KPIs examined include average listing price, booking activity by date, distribution of property prices, host ranking,
and property configuration metrics such as bedroom and bathroom counts. Geographic metrics were also analyzed to identify neighborhood-level listing density and pricing variations.

The expected outcome of this project is to provide a clear, data-driven view of the Airbnb market, highlight patterns in customer demand, reveal top-performing hosts and neighborhoods,
and support stakeholders in making informed pricing, investment, and property management decisions.

  
---

# Visualizations and Insights
### Line Chart – Average Price Over Time
- **Chart type:** Line Chart  
- **Purpose:** Show price trends over time.  
- **Key metrics:** Average Price, Week of Date  
- **Insight derived:** Prices stay mostly stable with minor fluctuations.  
- **Why chosen:** Best for visualizing time-based trends.

### Calendar Heat Map – Booking Density
- **Chart type:** Heat Map  
- **Purpose:** Show activity across days and dates.  
- **Key metrics:** Booking/price activity  
- **Insight derived:** Certain days show higher activity.  
- **Why chosen:** Quickly highlights high vs. low activity periods.

### Histogram – House Price Distribution
- **Chart type:** Histogram  
- **Purpose:** Show price distribution.  
- **Key metrics:** Price, Count of Listings  
- **Insight derived:** Most listings fall in lower-to-mid price ranges.  
- **Why chosen:** Ideal for visualizing numeric distributions.

### Bar Chart – Top 5 Hosts
- **Chart type:** Horizontal Bar Chart  
- **Purpose:** Rank the top hosts.  
- **Key metrics:** Host Name, Performance Val


---

# Dashboard Screenshot

<img width="1366" height="768" alt="Annotation 2025-12-02 020617" src="https://github.com/user-attachments/assets/666f7728-4600-4712-86a7-883d13e4544e" />

# Folder Structure:
```
/tableau-project
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── workbook/
│   └── project.twb
│
├── docs/
│   └── report.md
│
└── images/
    |── dashboard.png
 
```

---

# Future Improvements

- Add new dashboards or KPIs
- Include predictive analytics
- Improve interactivity with parameters
- Automate refresh using Tableau Prep
- Expand geographical or temporal granularity
