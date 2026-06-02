# Netflix Movies and TV Shows Data Analysis using SQL


##  Overview

This project focuses on analyzing Netflix's Movies and TV Shows dataset using SQL to uncover meaningful insights and answer real-world business questions. The analysis explores content distribution, ratings, genres, countries, release trends, and other key metrics to better understand Netflix's content library.

The project demonstrates practical SQL skills such as data filtering, aggregation, window functions, string manipulation, date functions, subqueries, and Common Table Expressions (CTEs).

---

##  Project Objectives

- Examine the distribution of Movies and TV Shows on Netflix.
- Identify the most frequently assigned ratings across content types.
- Analyze content based on release year, duration, and country.
- Explore genre popularity and regional content trends.
- Investigate directors, actors, and content performance.
- Classify content using keyword-based categorization.

---

##  Dataset

**Source:** Netflix Movies and TV Shows Dataset (Kaggle)

The dataset contains information such as:

- Show ID
- Content Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

---

##  Database Schema

```sql
DROP TABLE IF EXISTS netflix;

CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);
```

---

##  Business Questions Solved

### 1. Movies vs TV Shows Distribution
Analyze the overall distribution of content types available on Netflix.

### 2. Most Common Ratings
Determine the most frequently occurring rating for Movies and TV Shows.

### 3. Movies Released in a Specific Year
Retrieve all movies released in a selected year.

### 4. Top 5 Countries by Content Count
Identify countries contributing the highest number of titles to Netflix.

### 5. Longest Movie on Netflix
Find the movie with the maximum duration.

### 6. Content Added in the Last Five Years
Analyze recently added content available on the platform.

### 7. Content Directed by Rajiv Chilaka
List all Movies and TV Shows directed by Rajiv Chilaka.

### 8. TV Shows with More Than Five Seasons
Identify long-running TV Shows available on Netflix.

### 9. Genre-wise Content Distribution
Calculate the number of content titles within each genre.

### 10. India's Top Content Release Years
Determine the years with the highest percentage of content releases from India.

### 11. Documentary Movies
Retrieve all movies categorized as documentaries.

### 12. Content Without Director Information
Identify records where director details are missing.

### 13. Salman Khan Movies in the Last Decade
Analyze content featuring Salman Khan released during the last ten years.

### 14. Top 10 Actors in Indian Content
Find actors with the highest number of appearances in Indian-produced Netflix titles.

### 15. Content Classification Based on Keywords
Categorize content as:
- **Bad** → Contains keywords like *kill* or *violence*
- **Good** → Does not contain those keywords

---

##  Key Insights

### Content Distribution
Netflix hosts a large and diverse collection of both Movies and TV Shows across multiple genres and countries.

### Audience Targeting
Rating analysis helps understand the intended audience segments for Netflix content.

### Regional Analysis
Country-level analysis highlights regions contributing the most content to Netflix's catalog.

### Genre Trends
Genre distribution reveals the most popular categories available on the platform.

### Content Classification
Keyword-based categorization provides insights into the nature and themes of Netflix content.

---

##  SQL Concepts Applied

This project demonstrates the use of:

- SELECT Statements
- WHERE Clause
- ORDER BY
- GROUP BY
- Aggregate Functions
- CASE Statements
- Window Functions
- Common Table Expressions (CTEs)
- String Functions
- Date Functions
- Subqueries
- Data Transformation Techniques

---

##  Conclusion

Through SQL-driven analysis, this project uncovers valuable insights from Netflix's content library. The findings provide a deeper understanding of content distribution, audience targeting, genre trends, regional production patterns, and content characteristics.

This project serves as a practical example of applying SQL to solve business problems and generate actionable insights from real-world data.

---

## 🛠 Tools & Technologies

- PostgreSQL
- SQL
- Netflix Dataset (Kaggle)
- GitHub

---

## 📈 Skills Demonstrated

- Data Analysis
- SQL Querying
- Data Cleaning
- Data Exploration
- Business Problem Solving
- Database Management
- Insight Generation
