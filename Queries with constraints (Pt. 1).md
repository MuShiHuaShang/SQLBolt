## SQL Lesson 2: Queries with constraints (Pt. 1)
### 1. Find the movie with a row id of 6
```SQL
SELECT * 
FROM movies
WHERE Id = 6;
```

### 2. Find the movies released in the years between 2000 and 2010 
```SQL
SELECT * 
FROM movies
WHERE Year BETWEEN 2000 AND 2010;
```

### 3. Find the movies not released in the years between 2000 and 2010
```SQL
SELECT * 
FROM movies
WHERE Year NOT BETWEEN 2000 AND 2010;
```

### 4. Find the first 5 Pixar movies and their release year
```SQL
SELECT title, year
FROM movies
LIMIT 5;
```