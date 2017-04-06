GetOrganizationCatalogueInfo
=============================

Метод для получения данных о структуре организации.
Имя ресурса: /V1/Organizations/GetOrganizationCatalogueInfo
HTTP метод: GET
Параметры строки запроса:

 - partyId – идентификатор организации.
 
В запросе должен присутствовать HTTP-заголовок Authorization с необходимыми данными для авторизации.
В ответе сервер вернет структуру :doc:`OrganizationCatalogueInfo <../structures/OrganizationCatalogueInfo>`.