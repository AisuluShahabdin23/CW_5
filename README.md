# Курсовой проект по работе с базами данных
Получение данных о работодателях и их вакансиях с сайта hh.ru. Спроектированы таблицы в БД PostgreSQL для хранения полученных данных о работодателях и их вакансиях.

**Реализовано:**
- Получает список всех компаний и количество вакансий у каждой компании
- Получает список всех вакансий с указанием названия компании, названия вакансии и зарплаты и ссылки на вакансию.
- Получает среднюю зарплату по вакансиям.
- Получает список всех вакансий, у которых зарплата выше средней по всем вакансиям.
- Получает список всех вакансий, в названии которых содержатся переданные слова.

**Шаблон для файла конфигурации файла database.ini для подключения к БД:**
- [postgresql]
- host=localhost
- user=имя_пользователя
- password=ваш_пароль
- port=5432
