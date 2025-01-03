# Netflix Movies and TV Shows Data Analysis using SQL
![netflix_logo](https://github.com/ABHI-RAJ-9053/netflix_data_analysis_project/blob/main/netflix_logo02.png)
## Overview
<p>This project focuses on analyzing Netflix's movies and TV shows dataset using SQL to uncover valuable insights and address key business questions. This README outlines the project's objectives, the business problems tackled, the solutions implemented, and the resulting findings and conclusions.</p><br>
<h2> Objectives </h2>
<ul>
  <li>Analyze the distribution of content types (movies vs TV shows).</li>
  <li>Identify the most common ratings for movies and TV shows.</li>
  <li>List and analyze content based on release years, countries, and durations.</li>
  <li>Explore and categorize content based on specific criteria and keywords.</li></ul>
<h2> Dataset</h2>
The data for this project is sourced from the Kaggle dataset:
<ul><li>Dataset Link : <a href = 'https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download' > Movies Dataset</a></li></ul>
<h2> Schemas </h2>
```sql

CREATE TABLE netflix
(
	show_id	VARCHAR(5),
	type    VARCHAR(10),
	title	VARCHAR(250),
	director VARCHAR(550),
	casts	VARCHAR(1050),
	country	VARCHAR(550),
	date_added	VARCHAR(55),
	release_year	INT,
	rating	VARCHAR(15),
	duration	VARCHAR(15),
	listed_in	VARCHAR(250),
	description VARCHAR(550)
);

```
