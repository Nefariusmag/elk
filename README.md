---
Info:
---
Контейнеры для развертывания ELK
---
Files:
---
docker-compose.yml
logstash/logstash.conf
---
Setup:
---
Установить docker и docker-compose

https://docs.docker.com/install/
https://docs.docker.com/compose/install/

Создать папку для хранения базы elasticsearch:
mkdir esdata1

Запустить контейнеры:
docker-compose up -d
---
History:
---
