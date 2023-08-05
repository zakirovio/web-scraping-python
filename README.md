# Web-scraping

Переделал репозиторий и и начал собирать проект таким образом, чтобы можно было тестировать сайты и API отправляя
запросы, как синхронно, так и асинхронно.
Можно скачать репозиторий и спокойно сделать разовый скрапинг веб страницы или разработать полноценный скрапер.

Давно хотел сделать что-то подобное, чтобы при выполнении заказов был бы один проект с нужными зависимостями и уже 
определенными заранее функциями; а на диске не копилось множество папок с виртуалками и разного рода кодом, где каждый
раз нужно было бы определять один и тот же функционал.

В модуле ```utils.py``` пакета ```utils``` начал собирать разные функции, которые пригодятся для скрапинга или других 
задач. По ходу дела можно добавить еще множество утилит. Пока только настроен pytesseract на распознавания автомобильных
номеров и функция для построчной записи в Excel таблицу и еще некоторые функции, которые пригодились мне при скрапинге
сайтов. 