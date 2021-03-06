# Назва проєкту. Запити зацікавлених осіб

## Вступ

Документ містить опис запитів зацікавлених осіб, щодо проекту системи управління відкритими даними, що перебуває в розробці.

### Мета 

Створення та впровадження системи управління відкритими даними "Industrial Eden", призначенням якої є забезпечення реалізації життєвого циклу відкритих даних в індустрії розваг.

### Контекст

Цей документ пов’язаний з такими видами проектів:
  - сховища, які збирають метадані продуктів, що складають індустрію розваг. Наприклад, назва, жанр, тривалість, альбом, група і т.д.
  - системи організації та проведення опитування.

Перелік вимог, перерахованих в цьому документі, є основою технічного завдання на розробку системи управління відкритими даними "Industrial Eden".

### Основні визначення та скорочення

[Індустрія розваг](https://leksika.com.ua/14361106/turizm/industriya_dozvillya) - діяльність, спрямована на організацію розваг під час відпочинку людини.

[Метадані](https://uk.wikipedia.org/wiki/%D0%9C%D0%B5%D1%82%D0%B0%D0%B4%D0%B0%D0%BD%D1%96) - це дані, що характеризують або пояснюють інші дані.

Структура даних — це спосіб організації даних в комп'ютерах. Часто разом зі структурою даних пов'язується і специфічний перелік операцій, що можуть бути виконаними над даними, організованими в таку структуру.

[Формати даних](https://uk.wikipedia.org/wiki/%D0%A4%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8_%D0%B4%D0%B0%D0%BD%D0%B8%D1%85) — сукупність регламентованих в архітектурі ЕОМ структур для представлення різних за специфікою обробки та представлення видів інформації (цілих чисел, дробових чисел, текстових рядків тощо).

[База даних](https://uk.wikipedia.org/wiki/%D0%91%D0%B0%D0%B7%D0%B0_%D0%B4%D0%B0%D0%BD%D0%B8%D1%85) (англ. database) – сукупність даних, організованих відповідно до концепції, яка описує характеристику цих даних і взаємозв'язки між їх елементами.

[Система управління базами даних](https://ru.wikipedia.org/wiki/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0_%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_%D0%B1%D0%B0%D0%B7%D0%B0%D0%BC%D0%B8_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85), скор. СУБД (англ. Database Management System, скор. DBMS) - сукупність програмних і лінгвістичних засобів загального або спеціального призначення, що забезпечують управління створенням і використанням баз даних.</br>
СУБД - комплекс програм, що дозволяють створити базу даних (БД) і маніпулювати даними (вставляти, оновлювати, видаляти і вибирати). Система забезпечує безпеку, надійність зберігання і цілісність даних, а також надає кошти для адміністрування БД.

Статистичний аналіз – аналіз статистичних даних з метою встановлення закономірностей стану та розвитку процесів, зв'язку між ними, структурних зрушень, їх прогнозування.

[Розробник програмного забезпечення](https://uk.wikipedia.org/wiki/%D0%A0%D0%BE%D0%B7%D1%80%D0%BE%D0%B1%D0%BA%D0%B0_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE_%D0%B7%D0%B0%D0%B1%D0%B5%D0%B7%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%BD%D1%8F) (англ. software engineering, software development) — це людина, чий рід діяльності (професія) та процес, спрямований на створення та підтримку працездатності, якості та надійності програмного забезпечення, використовуючи технології, методологію та практики з інформатики, керування проектами, математики, інженерії та інших областей знання.

[Користувач](https://uk.wikipedia.org/wiki/%D0%9A%D0%BE%D1%80%D0%B8%D1%81%D1%82%D1%83%D0%B2%D0%B0%D1%87_(%D1%96%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D0%BA%D0%B0)) — людина, котра використовує комп'ютер або мережеву службу.

[Адміністратор бази даних](https://ru.wikipedia.org/wiki/%D0%90%D0%B4%D0%BC%D0%B8%D0%BD%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%82%D0%BE%D1%80_%D0%B1%D0%B0%D0%B7_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) (англ. Database administrator, DBA) - особа, що відповідає за вироблення вимог до бази даних, її проектування, реалізацію, ефективне використання і супровід, включаючи управління обліковими записами користувачів БД і захист від несанкціонованого доступу. Не менш важливою функцією адміністратора БД є підтримка цілісності бази даних.

### Посилання

*[Розділ містить повний список всіх документів, про які згадується.]*


## Короткий зміст

*[Розділ містить опис того, про що йдеться в еій частині цього документу, що залишилася. 
Також тут описана структура документу.]*

## Характеристика ділових процесів

*[В цьому розділі визначаються зовнішні фактори, що впливають на бізнес (бізнес-актори), 
та внутрішні фактори (робітники), дається загальна характеристика діяльності бізнес-акторів 
та робітників, яка здійснюється за допомогою бізнесу.*

*Дається опис бізнес-сценаріїв взаємодії бізнес-акторів, робітників і, можливо, інформаційної системи за допомогою наступної
специфікації:*

   
***ID:***
    
***НАЗВА:***
    
***УЧАСНИКИ:***

***ПЕРЕДУМОВИ:***

***РЕЗУЛЬТАТ:***

***ВИКЛЮЧНІ СИТУАЦІЇ:***

***ОСНОВНИЙ СЦЕНАРІЙ:***

*Кількість сценаріїв визначається у відповідності до специфіки завдання та необхідного 
рівня деталізації (зазвичай, 5-6 сценаріїв).*

## Короткий огляд продукту

*[Визначається границя системи та категорії її користувачів. Дається загальна характеристика категорій користувачів
системи]*

*[Нижче йде опис FURPS:]*


## Функціональність

*[Functionality (функциональні вимоги)]*

## Практичність

*[Usability (вимоги до зручності роботи)]*

## Надійність

*[Reliability (вимоги до надійності)]*

## Продуктивність

*[Performance (вимоги до продуктивності)]*

## Експлуатаційна придатність

*[Supportability (вимоги до підтримки)]*
