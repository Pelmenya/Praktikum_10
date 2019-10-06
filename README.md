# Практическая работа №10. 
https://pelmenya.github.io/Praktikum_10/
##  Тема: "Git, командная строка и регулярные выражения"
### Решены задачи:
* Создан репозитарий на GitHub рабочего приложения
* Разработаны алгоритмы валидации ввода данных в поля формы с примением паттернов регулярных выражений
* Опубликован проект на GitHub

### Описание алгоритмов валидации полей ввода:
**_Поле Имя:_**
* только кириллица;
* первая буква заглавная;
* можно ввести от 2 до 20 символов — это можно задать в атрибутах minlength и maxlength;
* возможна запись двойных имён — например Анна-Мария.

**_Поле Email:_**
* имя E-mail может начинаться только с латинской буквы
* имя E-mail может содержать латинские буквы, цифры, тире, точки
* имя E-mail точка и тире не могут идти друг за другом
* имя E-mail более одной точки подряд запрещено
* имя E-mail более одного подряд тире запрещено
* имя E-mail не может заканчиваться точкой или тире
* после имя E-mail  идет обязательный знак @
* имя домена E-mail может начинаться только с цифры или латинской буквы, содержать тире
* имя домена E-mail не может быть меньше двух знаков и оканчиваться тире
* может быть несколько доменов разделенных одной точкой
* домен состоит не менее чем из двух латинских символов

**_Поле Телефон:_**
Шаблон для телефона находит номера в таких форматах:
* +7(925)900-90-90;
* +7(925) 900-90-90;
* +7 925-900-90-90;
* +79259009090;
* 89259009090.
_Пробелы возможны._

**_Поле Сайт:_**
* адрес сайта должен начинаться с http:// или https://;
* www. — необязательная группа;
* IP-адрес — 255.255.255.255 или доменное имя — yandex.ru;
* порт — необязательная группа, порт начинается с двоеточия, за которым идут от 2 до 5 цифр;
* путь — последовательность из цифр, слешей и латинских букв, на конце которого может стоять решётка #.

_Примечание:_
* Регулярные выражения можно скопировать из файла index.html.
* Валидация осуществляется только с ипользованием HTML и CSS без применения JavaScript.
