# [Exercise](https://sqlbolt.com/lesson/filtering_sorting_query_results)
We will be using a database with data about some of Pixar's classic movies.
This exercise will only involve the Movies table.

## Questions & Answers

### List all directors of Pixar movies (alphabetically), without duplicates
```sql
SELECT DISTINCT director
FROM movies
ORDER BY director ASC;
```

### List the last four Pixar movies released (ordered from most recent to least)
```sql
SELECT *
FROM movies
ORDER BY year DESC
LIMIT 4;
```

### List the first five Pixar movies sorted alphabetically
```sql
SELECT *
FROM movies
ORDER BY title ASC
LIMIT 5;
```

### List the next five Pixar movies sorted alphabetically
```sql
SELECT *
FROM movies
ORDER BY title ASC
LIMIT 5 OFFSET 5;
```