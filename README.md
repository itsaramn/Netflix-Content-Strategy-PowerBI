# Netflix Content Strategy | PowerBI


## 📌 Project Scope
This project focuses on content strategy analysis for streaming platforms.
Netflix content data is used as a primary case study to analyze content growth, genre distribution, regional presence, and audience targeting strategies.

---

## 📊 Dashboard Overview
An interactive Power BI dashboard was developed to explore:
- Content growth trends over time
- Movies vs TV shows distribution
- Genre popularity and diversification
- Country-wise content contribution
- Audience maturity and content age categories

---

## 🧹 Data Preparation (Power Query)
- Handled missing and unknown metadata
- Created binary flags for Movies and TV Shows
- Normalized multi-valued genre data using a separate genre dimension table
- Engineered content age and categorized titles as Recent, Old, and Vintage
- Separated movie duration (minutes) and TV show duration (seasons)

---

## 📈 Key Insights
- Content production increased sharply after 2015
- TV shows have grown faster than movies in recent years
- The United States and India are the largest content-producing countries
- Most content targets mature audience ratings
- Recent content dominates the overall catalog

---

## 📁 Repository Structure

```
Streaming-Platform-Content-Strategy-PowerBI/
├── Dataset/
├── PowerBI/
├── Screenshots/
└── README.md
```


---

## 🚀 How to Use
1. Download the `.pbix` file
2. Open it in Power BI Desktop
3. Use slicers to explore insights by year, country, content type, and content age

---

## 📝 Notes
This dashboard is platform-agnostic. Netflix data was used as a representative dataset, but the same analytical approach can be applied to other streaming platforms.
