# DB_Lesson1
## Работа с данными из разных таблиц

Задание выполнено в Google Sheets.
С решением можно ознакомиться, перейдя по следующей ссылке :point_right: [Работа с данными из разных таблиц.](https://docs.google.com/spreadsheets/d/1eBSA7kCIXzy4LkidZZJNtwsVUf7RGRLv_R7_kWT2L_I/edit#gid=0)

---

## Описание
Документ состоит из листов:

* **SELECT** - вывод таблиц категории *"Чему будет равна выборка"*
  
  ```
     1. SELECT ФИО, Д/р, Адрес FROM Общий список
     2. SELECT ФИО, Статус FROM Общий список WHERE Адрес = «Можга»
     3. SELECT ФИО FROM Общий список WHERE Адрес = «Москва» AND Группа = «Работа»
     4. SELECT Д/р FROM Общий список WHERE Адрес = «Москва» OR Группа = «Работа»
  ```
* **JOIN** - вывод таблиц категории *"Что будет результатом следующих JOIN’ов"*

  ```
     1. INNER JOIN Люди, Адреса ON id = Чей адрес
     2. LEFT JOIN Люди, Адреса ON id = Чей адрес
     3. RIGHT JOIN Люди, Адреса ON id = Чей адрес
     4. FULL JOIN Люди, Адреса ON id = Чей адрес
  ```
* **Дополнительное задание** - *Что будет результатом выборки*

  ```
     SELECT ФИО, Адрес, Комментарий FROM Люди RIGHT JOIN Адреса ON id = Чей
     Адрес
  ```

* **Таблицы**