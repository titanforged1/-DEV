# -DEV
1. SELECT title, description FROM film;
2. SELECT * FROM film
WHERE length > 60 AND length < 70 ;
3.SELECT * FROM film
WHERE rental_rate = 0.99 AND replacement_cost = 12.99 OR rental_rate = 28.99 AND replacement_cost = 28.99 ;
4.SELECT * FROM customer
WHERE first_name = 'Mary' AND last_name = 'Smith';
5.SELECT * FROM film
WHERE NOT length > 50 AND rental_rate = 2.99 OR rental_rate = 4.99;
