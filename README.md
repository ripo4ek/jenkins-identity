# jenkins-identity

Этапы для развертывания:

1) Запустить через docker-compose up
2) Пароль admin admin
3) Открыть заготовленный пайплайн и запустить

Приложение спулит приложение для генерации аватар-изображений отсюда - https://github.com/ripo4ek/identify-app после чего запустит его внутри докер контейнеров.  Шаги для пайплайна находятся в файле Jenkinsfile из спулленого репозитория.
Уточнение: Будет использоваться докер установленный на локальной машине пользователя.

Jenkins - http://localhost:8080/
Приложение будет доступно по адресу - http://localhost:6565/
