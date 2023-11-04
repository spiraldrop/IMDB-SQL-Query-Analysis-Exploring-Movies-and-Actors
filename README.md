# IMDb-SQL-Query-Analysis-Exploring-Movies-and-Actors

This project focuses on SQL queries using IMDB data. It involves the analysis of various tables and databases using SQLite in a Jupyter Notebook. Below, you'll find a brief overview and the main tasks that have been accomplished.

## Overview

The project primarily utilizes SQL to query the IMDB database. It involves examining different tables, understanding the schema, and performing various SQL operations.

## Tasks Completed

1. **Overview of Tables**: The project begins with an overview of all the tables available in the IMDB database.

2. **Schema Analysis**: For each table, a detailed schema analysis is conducted to understand the structure of the data.

3. **Query 1**: The first query seeks to list all directors who directed a 'Comedy' movie in a leap year, returning director names, movie names, and years.

4. **Query 2**: The second query focuses on listing the names of all actors who played in the movie 'Anand' (1971).

5. **Query 3**: Query three seeks to list all actors who acted in a film before 1970 and in a film after 1990.

6. **Query 4**: This query lists all directors who directed 10 or more movies, ordered by the number of movies they directed, in descending order.

7. **Query 5 (Part A)**: For each year, it counts the number of movies in that year that had only female actors.

8. **Query 5 (Part B)**: A supplementary query is provided, counting the number of movies with only male actors for reference.

9. **Query 6**: This query identifies the films with the largest cast, returning the movie title and the size of the cast.

10. **Query 7**: Query 7 focuses on finding the decade with the largest number of films and the total number of films in that decade.

11. **Query 8**: Find all the actors that made more movies with Yash Chopra than any other director.

12. **Query 9**: This query returns all actors whose Shahrukh number is 2, where the Shahrukh number represents the length of the shortest path between the actor and Shahrukh Khan in the "co-acting" graph.

## Useful Tips

- Ensure proper preprocessing for the 'year' column in the 'Movie' table.
- Remove trailing spaces in text columns using the TRIM() function.
- When using COUNT(column), be aware that it won't consider "NULL" values; consider alternatives like COUNT(*).

Feel free to explore the project, analyze the queries, and learn from the SQL operations performed. Enjoy your exploration!
