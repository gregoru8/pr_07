# pr_07
# Лабораторная работа №7 PSQL
# Цель:
Разработка и реализация информационной системы для базы данных больницы. Включает в себя создание базы данных, таблиц, выполнение SQL-запросов и визуализацию данных.
## Ход работы:
Импортирт библиотеки psycopg2 
![image](https://github.com/user-attachments/assets/4ea4edc9-ef46-4d32-ae6d-e0fc5ccec816)
Подключение к БД
![image](https://github.com/user-attachments/assets/10fd2c80-ceca-4640-9c15-c040bcf0c6a6)
Выполнение запросов
![image](https://github.com/user-attachments/assets/6a93c78c-6236-4d6c-acf5-e7b40c39d089)
![image](https://github.com/user-attachments/assets/7fda8185-a350-4236-baf6-358c1521a166)
## Упражнение 1. Создание базы данных
![image](https://github.com/user-attachments/assets/520f1db2-5ce7-4b56-825f-6ef05a588413)
## Упражнение 2. Подключитение к серверу базы данных и распечатка его версии
![image](https://github.com/user-attachments/assets/602e8c31-e034-4e90-bc52-f4a7e3513ba3)
## Упражнение 3. Получение информации о больнице и врачах с использованием идентификаторов больницы и врача
![image](https://github.com/user-attachments/assets/570c4d8a-f394-474d-95ad-5572f3568f6a)
## Упражнение 4. Получение списка врачей по заданной специальности и зарплате
![image](https://github.com/user-attachments/assets/9a1713c9-b67f-446f-9b69-3b9e27ccfd10)
## Упражнение 5. Получение списка врачей из определённой больницы
![image](https://github.com/user-attachments/assets/4be16028-6b19-47e2-b90b-0abffd63b2eb)
## Упражнение 6. Обновление стажа врачу с ID 101 на 3 года
![image](https://github.com/user-attachments/assets/af95483f-c180-4a37-8540-5d4c96c412d1)

# Выполненине индивидуальных заданий
## ЗАДАНИЕ №1. Подключение к базе и создание таблицы "employee".
![image](https://github.com/user-attachments/assets/ebe0f6cc-5681-4469-a465-56cc2ab5abe0)

## ЗАДАНИЕ №2. Получение информации о больнице с ID=2.
![image](https://github.com/user-attachments/assets/87bf4e5c-fc34-4353-ba55-86fc30ef36d5)
![image](https://github.com/user-attachments/assets/970489ec-b7b6-48e9-a91b-842a93246e9a)

## ЗАДАНИЕ №3. Создание таблицы "Patient" с полями "ID", "NAME", "AGE".
![image](https://github.com/user-attachments/assets/00a83032-18ab-4d9b-9c9c-df77c11960cf)

## ЗАДАНИЕ №4. Получение списка всех врачей, работающих более 5 лет в "Mayo Clinic".
![image](https://github.com/user-attachments/assets/3db36ab7-fe75-4a03-b89d-aa6e1a45d27d)
![image](https://github.com/user-attachments/assets/ab9e7820-3e10-46a7-9378-8299286b3a59)

## ЗАДАНИЕ №5. Визуализация распределения зарплат врачей в виде столбчатой диаграммы.
![image](https://github.com/user-attachments/assets/7e03219f-b38e-4ff8-90c5-269e48e3cdc2)
![image](https://github.com/user-attachments/assets/a8126dd3-b8be-4c9d-b6b6-eede42deef11)
![image](https://github.com/user-attachments/assets/63aa0773-bdb9-4ca0-bfa1-0c9b5fd75958)

# Вывод:
В ходе работы было изучено импортирование и экспортирование данных в базу данных SQL. Также были приобретены навыки работы с внешними данными, преобразования их в нужный формат и интегрирования с существующими таблицами в базе данных.


## Выполненные задания:
1. Создание ERD диаграммы для базы данных.
2. Разработка SQL-скриптов для создания базы данных и таблиц.
3. Реализация заданий в Jupyter Notebook с подключением к базе данных, вставкой и обновлением данных, а также визуализацией информации.

## Структура репозитория:
- `erd_diagram.png` — ERD диаграмма схемы базы данных.
- `create_db_and_tables.sql` — SQL скрипт для создания базы данных и таблиц.
- `Glagolenko_Gregory_Stanislavovich.ipynb` — Jupyter Notebook с выполнением всех заданий.

## Как запустить:
1. Установите PostgreSQL и настройте доступ к базе данных.
2. Выполните SQL-скрипт `create_db_and_tables.sql` для создания базы данных и таблиц.
3. Откройте и выполните Jupyter Notebook для проверки выполнения заданий.
