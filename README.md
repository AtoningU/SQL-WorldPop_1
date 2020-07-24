# SQL-WorldPop_1
CodeAcademy SQL World Population Project
https://gist.github.com/67fd8654e1d3115350f6fc9712599791

SELECT DISTINCT year from population_years;

-- Add your additional queries below:

SELECT country, population
FROM population_years
WHERE country LIKE 'gabon';

SELECT *
FROM population_years
WHERE year = 2005
ORDER BY population ASC
LIMIT 10;

SELECT DISTINCT country
FROM population_years
WHERE population > 100.00000
AND year = 2010;

SELECT DISTINCT country
FROM population_years
WHERE country LIKE '%islands%';

SELECT *
FROM population_years
WHERE country = 'Indonesia'
AND year = 2000;

SELECT *
FROM population_years
WHERE country = 'Indonesia'
AND year = 2010;
