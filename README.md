--# SQL_LIKE_AND_ILIKE_OPERATORU
--SQL_LIKE_AND_ILIKE_OPERATORU ODEVI

-- Birinci seneryo
SELECT*FROM country
WHERE country LIKE 'A%a';

--İkinci seneryo
SELECT*FROM country
WHERE country LIKE '_____%n';

--üçüncü seneryo
SELECT*FROM film
WHERE title ILIKE '%t%t%t%t%';

--Dördüncü seneryo
SELECT*FROM film
WHERE title LIKE 'C%' AND length> 90 AND rental_rate=2.99;
