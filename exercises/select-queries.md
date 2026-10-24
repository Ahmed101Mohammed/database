# [Exercise](https://sqlbolt.com/lesson/select_queries_introduction#)
We will be using a database with data about some of Pixar's classic movies.
This exercise will only involve the Movies table.

## Questions & Answers

### Find the title of each film
```sql
SELECT title FROM movies;
```

### Find the director of each film
```sql
SELECT director FROM movies;
```

### Find the title and director of each film
```sql
SELECT title, director FROM movies;
```

### Find the title and year of each film
```sql
SELECT title, year FROM movies;
```

### Find all the information about each film
```sql
SELECT * FROM movies;
```