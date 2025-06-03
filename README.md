# 🎬 IMDB SQL Analysis Project

This project performs in-depth analysis of the IMDB movie dataset using **SQL** queries. It is structured around business-relevant questions related to production houses, movie genres, actor/actress performance, box office revenues, and more, with the goal of supporting data-driven decision-making for a movie production company (RSVP Movies).

## 🧩 Key Tables Analyzed

- `movie`
- `genre`
- `ratings`
- `names`
- `director_mapping`
- `role_mapping`

## 📊 Major Insights Extracted

- Yearly and monthly trends in movie releases
- Genre popularity and duration trends
- Production houses with the most hit or multilingual films
- Ranking of actors/actresses based on rating performance
- Identification of top-rated movies, directors, and companies
- Movie classification by success (Superhit, Hit, Flop)
- Rolling averages and running totals by genre

## 🛠️ Technologies Used

- **SQL** (MySQL-compatible syntax)
- `INFORMATION_SCHEMA` for metadata queries
- Window functions: `RANK()`, `DENSE_RANK()`, `ROW_NUMBER()`, `LEAD()`
- Aggregate functions: `AVG()`, `COUNT()`, `SUM()`, `MIN()`, `MAX()`
- Conditional logic via `CASE WHEN`

## 📌 Use Cases

This project supports:

- Strategic planning for new movie production
- Talent scouting (top actors, directors)
- Genre targeting based on audience response
- Partner identification among production companies
- Time series analysis of movie trends

## 🚀 Getting Started

To run this project:

1. Import the IMDB dataset into your SQL environment.
2. Open and execute `IMDB+question.sql` in your SQL client (e.g., MySQL Workbench, DBeaver, pgAdmin).
3. Review the output to interpret insights or export results for reporting.

## ⚠️ Notes

- Make sure your database schema is named `imdb` (as used in the SQL file).
- Some queries use functions like `POSITION()` and `DATEDIFF()` — ensure compatibility with your SQL engine.
- Clean and load data with proper data types (especially dates and numeric columns).

## 🏁 Outcome

By the end of this project, users gain a detailed understanding of the structure, performance, and business opportunities within the IMDB dataset, enabling strategic decision-making for content production and investment.

---

# RSVP-Movies-IMDb-Analytics-Case-Study
SQL-based project analyzing three years of IMDb data for RSVP Movies to support their 2022 global release strategy. Extracted insights on audience preferences, genre trends, and box office performance through advanced queries. Provided actionable recommendations for production and marketing strategies, backed by data-driven analysis and reporting.
