Веб-сайт с возможностью авторизации по номеру телефона и добавления рефералов.

Postman коллекция со всеми запросами: https://x77777-4939.postman.co/workspace/x-Workspace~f144622f-0f20-46dc-b193-67bdf283cb22/collection/40119855-c335f15c-4977-4235-9158-81c73a9fd7cb?action=share&creator=40119855

Я реализовывал backend, а frontend мне помогал писать ИИ помощник (не подумайте, что я знаю JS).

Адрес веб-сайта: http://188.253.17.179:8000/

'http://188.253.17.179:8000/' - GET запрос для получения главной страницы (home)
'http://188.253.17.179:8000/api-auth' - GET запрос для получения страницы аутентификации (auth)
'http://188.253.17.179:8000/api-auth' - POST запрос для аутентификации пользователя
'http://188.253.17.179:8000/api-auth' - POST запрос для верификации кода (идёт после аутентификации)
'http://188.253.17.179:8000/api-users' - GET запрос для получения данных пользователя
'http://188.253.17.179:8000/api-update-user' - PUT запрос для обновления данных пользователя
'http://188.253.17.179:8000/user_page' - GET запрос для получения страницы пользователя (user page)
