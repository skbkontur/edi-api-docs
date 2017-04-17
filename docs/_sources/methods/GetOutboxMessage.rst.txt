GetOutboxMessage
=================

Метод для получения содержимого исходящего сообщения.

Имя ресурса: **/V1/Messages/GetOutboxMessage**

HTTP метод: **GET**

Параметры строки запроса:

 - boxId – идентификатор ящика;
 - messageId – идентификатор сообщения.
 
В запросе должен присутствовать HTTP-заголовок ``Authorization`` с необходимыми данными для авторизации.
В ответе сервер вернет структуру :doc:`OutboxMessageEntity <../structures/OutboxMessageEntity>`.