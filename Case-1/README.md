##  Анализ данных и SQL- запросы  

### 1. Есть следующие датасеты c данными о продажах в онлайн-магазине в формате csv файла:

- `products` (товары) 

- `orders` (заказы)  
 
- `order_items` (позиции заказов)  

- `customers` (покупатели)

- `categories` (категории товаров)

### 2. Наша задача:  

Написать SQL запросы для получения следующих данных из датасетов выше:  

- Количество уникальных пользователей за последние 30 дней.  
- Количество покупок и общая сумма продаж за последние 30 дней.  
- Средний чек и средний LTV для каждой категории продуктов.  
- Топ-5 продуктов по количеству покупок и выручке за последние 30 дней.  
- Сегментировать пользователей на группы по частоте использования продукта и выявить основные различия между этими группами.  

План работы:  

- создадим базу данных sqlite3 botdatabase.db;  
- в базе данных создадим таблицы: products, orders, order_items, customers, categories;  
- загрузим в созданные таблицы файлы: products.csv, orders.csv, order_items.csv, customers.csv, categories.csv;  
- напишем SQL запросы для получения данных.  

### 3.  Вот что у нас получилось:  

- [Решение](https://github.com/moseevaevgeniya/EasyBot/blob/8deef00569ec56602048ebb5904be2be01383052/Case-1/Test_Easy_bot-1.ipynb)

### 4. Стеки: 
- Jupyter-notebook,Python,sqlite3, pandas  
