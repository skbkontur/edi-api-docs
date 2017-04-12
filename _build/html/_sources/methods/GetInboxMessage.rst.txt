GetInboxMessage
================

Метод для получения содержимого входящего сообщения.

Имя ресурса: **/V1/Messages/GetInboxMessage**

HTTP метод: **GET**

Параметры строки запроса:

 - boxId – идентификатор ящика;
 - messageId – идентификатор сообщения.
 
В запросе должен присутствовать HTTP-заголовок ``Authorization`` с необходимыми данными для авторизации.
В ответе сервер вернет структуру :doc:`InboxMessageEntity <../structures/InboxMessageEntity>`.