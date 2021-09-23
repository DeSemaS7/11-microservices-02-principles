# Задача 1: API Gateway

Под описанные требования подходят почти все современные Api gateway. 
<p>Я бы остановил свой выбор на Kong Gateway, ввиду большой популярности. 
<p>Так же, в случае использования облачных платформ, можно использовать инструменты непосредственно от поставщиков, например Apigee или Amazon API Gateway.
<p> Ещё, как я понял, ничего не мешает построить гейт средствами nginx или haproxy.</p>

# Задача 2: Брокер сообщений

Хорошим выбором станет RabbitMQ.
<p> Он умеет кластеризироваться для отказоустойчивости, 
по умолчанию хранит данные на диске, имеет систему разделения прав, различные модели доставки сообщений а так же поддерживает почти все основные языки. 

