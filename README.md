# Netflix Movies and TV Shows Data Analysis using SQL

![netflix_logo](https://github.com/ABHI-RAJ-9053/netflix_data_analysis_project/blob/main/netflix_logo02.png)

## Overview
This project focuses on analyzing Netflix's movies and TV shows dataset using SQL to uncover valuable insights and address key business questions. This README outlines the project's objectives, the business problems tackled, the solutions implemented, and the resulting findings and conclusions.

## Objectives
- Analyze the distribution of content types (movies vs. TV shows).
- Identify the most common ratings for movies and TV shows.
- List and analyze content based on release years, countries, and durations.
- Explore and categorize content based on specific criteria and keywords.

## Dataset
The data for this project is sourced from the Kaggle dataset:
- [Movies Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)

## Schemas

Here is the schema used for the Netflix dataset:

```sql
CREATE TABLE netflix (
    show_id        VARCHAR(5),
    type           VARCHAR(10),
    title          VARCHAR(250),
    director       VARCHAR(550),
    casts          VARCHAR(1050),
    country        VARCHAR(550),
    date_added     VARCHAR(55),
    release_year   INT,
    rating         VARCHAR(15),
    duration       VARCHAR(15),
    listed_in      VARCHAR(250),
    description    VARCHAR(550)
);

<h2>Business Problems and Solutions</h2>
<h3>1. Count the Number of Movies vs TV Shows</h3>
```sql
CREATE TABLE netflix (
    show_id        VARCHAR(5),
    type           VARCHAR(10),
    title          VARCHAR(250),
    director       VARCHAR(550),
    casts          VARCHAR(1050),
    country        VARCHAR(550),
    date_added     VARCHAR(55),
    release_year   INT,
    rating         VARCHAR(15),
    duration       VARCHAR(15),
    listed_in      VARCHAR(250),
    description    VARCHAR(550)
);
```sql
SELECT 
    type,
    COUNT(*)
FROM netflix
GROUP BY 1;
);

