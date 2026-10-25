# [Exercise](https://sqlbolt.com/lesson/select_queries_with_constraints_pt_2)
We will be using a database with data about some of Pixar's classic movies.
This exercise will only involve the Movies table.

## Questions & Answers

### Find all the Toy Story movies 
```sql
SELECT * 
FROM movies
WHERE title LIKE "%toy story%";
```

### Find all the movies directed by John Lasseter
```sql
SELECT * 
FROM movies
WHERE director LIKE "%john lasseter%";
```

### Find all the movies (and director) not directed by John Lasseter  
```sql
SELECT * 
FROM movies
WHERE director NOT LIKE "%john lasseter%";
```

### Find all the WALL-* movies
```sql
SELECT * 
FROM movies
WHERE title LIKE "wall-%";
```