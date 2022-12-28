# Домашнее задание к занятию "`12.3. «Реляционные базы данных: SQL. Часть 1`" - `Александр Бакунин`

---

### Задание 1


![alt text](https://github.com/AleksandrBakunin/SQL.-1/blob/main/img/SQL1%20-%201.JPG)

select distinct district from address where district like 'K%a' and district not like '% %';

---

### Задание 2


![alt text](https://github.com/AleksandrBakunin/SQL.-1/blob/main/img/SQL1%20-%202.JPG)

select payment_id, customer_id, staff_id, rental_id, amount, cast(payment_date as datetime), last_update from payment where payment_date between '2005-06-15 00:00:00' and '2005-06-18 23:59:59' and amount > 10;

---

### Задание 3

select * from rental order by rental_date desc limit 5;

---

### Задание 4

select customer_id, store_id, lower(first_name), lower(last_name), replace(first_name, 'L', 'P'), email, address_id, active, create_date, last_update
from customer where first_name like 'KELLY' or first_name like 'WILLIE';


