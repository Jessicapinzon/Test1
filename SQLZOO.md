
# Sección 01. SELECT basics

## Pregunta 01

The example uses a WHERE clause to show the population of 'France'. Note that strings should be in 'single quotes';

Modify it to show the population of Germany

```sql
SELECT population
FROM world
WHERE name = 'Germany'
```

## Pregunta 02

Checking a list The word IN allows us to check if an item is in a list. The example shows the name and population for the countries 'Brazil', 'Russia', 'India' and 'China'.

Show the name and the population for 'Sweden', 'Norway' and 'Denmark'

```sql
SELECT name, population 
FROM world
WHERE name IN ('Sweden', 'Norway', 'Denmark')
```
