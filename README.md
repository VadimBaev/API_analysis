# API_analysis
В качестве тестового задания необходимо было сделать:
- выполнить подключение к любому API из раздела Shopping https://github.com/public-apis/public-apis#shopping
- получить данные 
- выполнить базовый анализ данных и сделать общие выводы 

Я попробовал подключиться к нескольким магазинам и вот что было:

Best Buy.
На этапе регистрации система не принимала вводимый мной телефонный номер, поэтому подключиться не удалось

Digi-Key.
Зарегистрировался. Получил Client ID и Client Secret, но получить access token для загрузки данных не удалось, т.к. у них поменялось API и те шаги, которые приводили к получению токена на срабатывали. Пытался решить проблему с помощью инофрмации по ссылке - не получилось
https://github.com/peeter123/digikey-api/issues/3

eBay.
Нужно ждать одобрения регистрации. Пришло спустя 1,5 дня, параллельно пробовал подключиться к другим магазинам.

Lazada.
Удалось подключиться и получить данные. Для этого зарегистрировался на Open Platform. Зарегистрировал app и скачал клиент. Получил необходимые данные, выполнил базоывй анализ и сделал некоторые выводы. Подробности в ноутбуке
