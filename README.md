# elk

### Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.


![Screenshot_15](https://github.com/user-attachments/assets/fba4d9f8-3191-4af6-a0d4-64cf5b2127e2)



### Задание 2. Kibana

Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.


![Screenshot_24](https://github.com/user-attachments/assets/c7d6a696-d8cb-4c7e-a83b-b4671bb0ea4a)

Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.



![Screenshot_87](https://github.com/user-attachments/assets/a395fe02-a7c1-4afe-8dae-9f975eec731e)


### Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.



![Screenshot_65](https://github.com/user-attachments/assets/05e9cd1c-16b3-44b1-8651-ae40dc92b4cd)
