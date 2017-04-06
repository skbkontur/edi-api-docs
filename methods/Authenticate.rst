Authenticate
=============

Метод для получения авторизационного токена.
Имя ресурса: /V1/Authenticate
HTTP метод: POST
В запросе должен присутствовать HTTP-заголовок Authorization с параметрами konturediauth_api_client_id, konturediauth_login и konturediauth_password (см. раздел :doc:`Авторизация <../Authorization>`).
Ответом от сервера будет строка в кодировке UTF-8 – авторизационный токен.