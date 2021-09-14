**get запросы пользователей, yandex и google роботов с кодом ответа 404 (не найдены картинки, разделы):**
* tsarmindal.ru 66.249.70.88 - - [16/Jul/2021:00:00:34 +0300] "GET /upload/iblock/c46/%D1%84%D0%B8%D1%82%D0%BF%D0%B0%D1%80%D0%B0%D0%B4-60-%D1%81%D0%B0%D1%88%D0%B5.jpg HTTP/1.1" 404 184175 "-" "Googlebot-Image/1.0" 74006 46666:19999
* tsarmindal.ru 66.249.70.88 - - [16/Jul/2021:00:02:49 +0300] "GET /catalog/kosmetika-dnevnoj-uhod-dlya-lica/ HTTP/1.1" 404 186099 "-" "Mozilla/5.0 (Linux; Android 6.0.1; Nexus 5X Build/MMB29P) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.90 Mobile Safari/537.36 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)" 280719 123334:16666
* и т.д.

**get запрос с кодом ответа 500 (внутренняя ошибка сервера):**
* tsarmindal.ru 5.101.19.183 - - [16/Jul/2021:00:09:40 +0300] "GET /brands/ HTTP/1.1" 500 214966 "https://tsarmindal.ru/contacts/" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/86.0.4240.111 Safari/537.36" 115410 66666:29999

**get запрос с кодом ответа 504 (прокси не дождался ответа):**
* tsarmindal.ru 63.143.42.245 - - [16/Jul/2021:00:01:37 +0300] "GET / HTTP/1.1" 504 299920 "http://tsarmindal.ru" "Mozilla/5.0+(compatible; UptimeRobot/2.0; http://www.uptimerobot.com/)" 596662 83333:49999

**get запросы с ответом 301 и итоговым перенаправление на главную страницу:**
1. tsarmindal.ru 66.249.70.88 - - [16/Jul/2021:00:06:37 +0300] "GET /catalog/orekhi/mindal/mindal-zharenyj/ HTTP/1.1" 301 - "-" "Mozilla/5.0 (Linux; Android 6.0.1; Nexus 5X Build/MMB29P) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.90 Mobile Safari/537.36 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)" 40797 23333:13333
1. tsarmindal.ru 66.249.70.88 - - [16/Jul/2021:00:06:37 +0300] "GET /product/mindal-zharenyj/ HTTP/1.1" 404 184615 "-" "Mozilla/5.0 (Linux; Android 6.0.1; Nexus 5X Build/MMB29P) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.90 Mobile Safari/537.36 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)" 70451 40000:16666
1. tsarmindal.ru 63.143.42.245 - - [16/Jul/2021:00:06:37 +0300] "GET / HTTP/1.1" 200 299920 "http://tsarmindal.ru" "Mozilla/5.0+(compatible; UptimeRobot/2.0; http://www.uptimerobot.com/)" 246716 100000:33334
