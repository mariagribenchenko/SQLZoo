# SELECT From World


## Ejercicio 01.

```sql
SELECT name, continent, population
FROM world
```

## Ejercicio 02.

```sql
SELECT name
FROM world
WHERE population >= 200000000
```

## Ejercicio 03.

```sql
SELECT name, gdp/population AS per_capita_GDP
FROM world
WHERE population >= 200000000
```
