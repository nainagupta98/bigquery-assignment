# bigquery-assignment
CODE NO.1 
SELECT * FROM `bigquery-public-data.census_bureau_international.midyear_population_agespecific` LIMIT 5
CODE NO.2
SELECT avg(population) FROM `bigquery-public-data.census_bureau_international.midyear_population_agespecific` LIMIT 5
CODE NO.3
SELECT avg(age) FROM `bigquery-public-data.census_bureau_international.midyear_population_agespecific` LIMIT 3
CODE 4
SELECT COUNT(population) FROM `bigquery-public-data.census_bureau_international.midyear_population_agespecific` LIMIT 5
CODE NO.5
SELECT sum(population) FROM `bigquery-public-data.census_bureau_international.midyear_population_agespecific` LIMIT 5
CODE NO.6
SELECT max(age) FROM `bigquery-public-data.census_bureau_international.midyear_population_agespecific` LIMIT 5
CODE NO.7
SELECT MIN(population) FROM `bigquery-public-data.census_bureau_international.midyear_population_agespecific` LIMIT 5
CODE NO.8
SELECT sum(population) FROM `bigquery-public-data.census_bureau_international.midyear_population_agespecific`
where age > 30
 LIMIT 5
CODE NO.9
SELECT * FROM `bigquery-public-data.census_bureau_international.midyear_population_agespecific`
where age > 25
order by age
 LIMIT 5
CODE NO.10
SELECT * FROM `bigquery-public-data.census_bureau_international.midyear_population_agespecific`
where year > 2001 and age > 25
order by age
 LIMIT 5
