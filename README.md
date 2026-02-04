# YouTube Trending Data Analysis

## Project Overview
This project performs exploratory data analysis (EDA) on YouTube trending video data to understand engagement patterns and relationships between popularity metrics such as views, likes, and comments.

The analysis focuses on identifying category-wise engagement trends and understanding how videos gain traction on the YouTube trending platform.

---

## Dataset Description
- Source: YouTube Trending Videos Dataset / YouTube Data API v3 (metadata)
- Each row represents a single trending video.
- Key attributes include:
  - Video ID and Category
  - Views, Likes, and Comment Count
  - Publish Time and Trending Date

---

## Objectives
- Analyze relationships between views, likes, and comments
- Compare engagement patterns across video categories
- Study how quickly videos appear on the trending page
- Identify general trends in user engagement behavior

---

## Data Cleaning & Transformation
The following preprocessing steps were applied:
- Removed duplicate entries for videos appearing on trending multiple days
- Handled missing or null engagement values
- Converted date fields to proper datetime formats
- Created a derived feature:
  - **Days to Trend**: Difference between publish date and trending date

These steps ensured a clean, structured dataset suitable for analysis.

---

## Exploratory Data Analysis
The analysis includes:
- Distribution analysis of views, likes, and comments
- Category-wise comparison of average engagement metrics
- Scatter plot analysis of views vs likes and views vs comments
- Correlation analysis among engagement metrics using a heatmap

---

## Key Insights
- Views and likes show a strong positive relationship
- Comment count shows higher variability compared to views and likes
- Engagement patterns differ significantly across video categories
- Most trending videos appear shortly after being published

---

## Limitations
- Dataset includes only trending videos, not the full YouTube population
- Analysis identifies associations, not causation
- External factors such as promotion or creator popularity are not modeled

---

## Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib & Seaborn for visualization
- Jupyter Notebook

---

## Conclusion
This project demonstrates how exploratory data analysis can be used to study digital content engagement and uncover patterns in user interaction on large-scale media platforms like YouTube.
