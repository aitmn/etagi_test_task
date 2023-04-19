# etagi_test_task
Необходимо написать запросы, которые выводят:
1.	Город и номер телефона клиентов только с фамилией «Попов»

2.	Количество клиентов из Тюмени

```
1. SELECT city, phone FROM customers WHERE fio = 'Попов';

2.SELECT COUNT(*) FROM customers WHERE city = 'Тюмень';
```
