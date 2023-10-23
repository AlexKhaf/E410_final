Задание:

Как системному администратору данной организации вам поставлена задача собрать на докер образ Django
(Linux, nginx, Django, Postgres, Gunicorn) сервера. Все нужные сервисы должны быть проброшены на хост по стандартным
портам, реализация HTTPS не требуется, версии Django, nginx и Postgres не имеют значения, как и версия ядра Linux.
В проекте просто должна работать админка с заранее прописанным логином и паролем.

#### Системные требования:

- Linux система для установки: 
(тестировалась и разрабатывалась на Ubuntu 22.04.3 LTS в витуальной машине Oracle VM VirtualBox) 
- Docker (тестировалась и разрабатывалась на v. 24.0.5)
- Умение работы с Github и Docker

#### Запуск приложения:

- Cоздаем директорию для проекта
- Загружаем проект из git в созданную директорию:
https://github.com/AlexKhaf/E410_final.git
- Запускаем из созданной директории файл start_me командой: source start_me или . start_me
- Дожидаемся окончания настройки системы
- Переходим в браузер и открываем адрес 127.0.0.1/admin/ 

## Данные для входа в админку Django:
логин: admin  
пароль: admin
