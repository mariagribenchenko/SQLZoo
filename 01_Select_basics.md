
# SELECT basics

## Ejercicio 01.

```sql
SELECT population 
FROM world
WHERE name = 'Germany'
```

## Ejercicio 02.

```sql
SELECT name, population
FROM world
WHERE name IN ('Sweden', 'Norway', 'Denmark')
```

## Ejercicio 03.

```sql
SELECT name, area 
FROM world
WHERE area BETWEEN 200000 AND 250000
```
