# Docker_task_B8.5.1

Задание на самопроверку. Отредактировать docker-compose.yml:

В docker-compose.yml из задания предыдущего юнита необходимо:

1. Добавить healthcheck в сервис redis. Подсказка: для этого используется функция redis-cli ping.s.
2. Добавить в depends_on сервиса web проверку на состояние redis контейнера.
