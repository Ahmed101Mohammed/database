# [Exercise](https://sqlbolt.com/lesson/select_queries_introduction#)
We will be using a database with data about some of Pixar's classic movies for 
most of our exercises. This first exercise will only involve the Movies table, 
and the default query below currently shows all the properties of each movie. 
To continue onto the next lesson, alter the query to find the exact information 
we need for each task.

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