# Stsiapan Sukach

### Contacts
* Telegram: @Stsiapan_Sukach
* Phone: +375 29 150 20 80
* Skype: live:stepansukac
* VK: [page](https://vk.com/id89240668)

### Hope's and wishes
My main goal of admission to the course is to improve my programming skills and successfully find a job.

### Skils
HTML5, CSS3, JS, Git, SQL

### Code exmaple
```SQL
    SELECT buy_book.buy_id, client.name_client, SUM(book.price * buy_book.amount) AS Стоимость
    FROM book JOIN buy_book
        ON book.book_id = buy_book.book_id
            JOIN buy
                ON buy_book.buy_id = buy.buy_id
                    JOIN client
                        ON buy.client_id = client.client_id
    GROUP BY buy_book.buy_id, client.name_client
    ORDER BY buy_book.buy_id
```

### Experience
Several simple one-page applications, copy loyout of [Telegram](https://github.com/Qry1/Qry1.github.io), fully completed all tasks from [HTMLAcademy](https://htmlacademy.ru/courses), finished course on Stepik [SQL](https://stepik.org/course/63054)

### Education
BNTU: ventilation, heat & gas supply engineer

### Foreign languages
B1 English level and B2 German level
