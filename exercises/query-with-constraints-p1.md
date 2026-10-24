# [Exercise](https://sqlbolt.com/lesson/select_queries_with_constraints)
We will be using a database with data about some of Pixar's classic movies.
This exercise will only involve the Movies table.

## Questions & Answers

### Find the movie with a row id of 6
```sql
SELECT * 
FROM movies
WHERE id = 6;
```

### Find the movies released in the years between 2000 and 2010
```sql
SELECT * 
FROM movies
WHERE year BETWEEN 2000 AND 2010;
```

### Find the movies not released in the years between 2000 and 2010 
```sql
SELECT * 
FROM movies
WHERE year NOT BETWEEN 2000 AND 2010;
```

### Find the first 5 Pixar movies and their release year
```sql
SELECT * 
FROM movies
WHERE id BETWEEN 1 AND 5;
```