# Заглушка для переезда Мнемо

Веб-версия Мнемо переехала:

- старый адрес: https://kartaviyukr.github.io/-/mnemo/
- новый адрес: **https://kartaviys.github.io/-/mnemo/**

Имя репозитория `kartaviyukr/-` GitHub заблокировал после переименования аккаунта, поэтому старый адрес
обслуживает сайт организации `kartaviyukr.github.io`: файл `-/mnemo/index.html` открывается по пути `/-/mnemo/`.

Страница читает прогресс (`mnemo.v1`, `mnemo.photos2`) из памяти браузера на старом адресе и передаёт его на
`https://kartaviys.github.io/-/mnemo/move.html#…`. Данные идут после `#`, поэтому на сервер они не уходят.
Если прогресса нет или он уже перенесён, страница сразу открывает новый адрес.

`.nojekyll` отключает обработку Jekyll. GitHub Pages: Deploy from a branch → `main`, папка `/ (root)`.
