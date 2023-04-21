# etagi_test_task

## Файл с чек-листами и тест кейсами
https://docs.google.com/spreadsheets/d/13bxraThNuLuaDvldEPdvtjcLLId0FgKNgP9upLHUOK8/edit?usp=sharing

## SQL Запросы
Необходимо написать запросы, которые выводят:
1.	Город и номер телефона клиентов только с фамилией «Попов»

2.	Количество клиентов из Тюмени

```
1. SELECT city, phone FROM customers WHERE fio = 'Попов';

2.SELECT COUNT(*) FROM customers WHERE city = 'Тюмень';
```
