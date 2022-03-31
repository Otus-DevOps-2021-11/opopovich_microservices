# opopovich_microservices
opopovich microservices repository

Docker-1 and Docker-2 homework

1)Научились работать с докер и докер хаб
2)Испытали много боли и поняли что методичка устарела
3)Залили свой образ в докер-хаб

Docker-3 homework

1)Научились собирать Docker образы для приложений
2)Оптимизировали Dockerfile
3)Опять испытали боль с устаревшей методой
4)Научились подключать docker volume

Docker-4 homework
1)Разобрались с сетями и docker-compose
2)Чтобы изменить имя проекта нужно запустить docker-compose с флагом -p или уже можно указать project_name рпямо в yaml

Monitoring homework

Подняли контейнер с prometheus и reddit
Не понял почему на странице 32 ui_health=0  и как вообще это работает.
Собрали хостовые метрики с помощью node exporter
Ссылка на образы docker.io/opopovich85

Logging homework

- Не удалось поработать с Kibana т.к fluentd не передает данные в эластик и ошибка не понятна
- Zipkin работает

Kubernetes-1 homework

- Долго пытался понять почему virtualbox nat ip одинаковый для всех нод

- Понял что нужно поднимать кластер с --apiserver-advertise-address

- Запустил кластер и протестировал его работу
