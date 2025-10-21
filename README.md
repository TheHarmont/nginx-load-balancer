# Nginx load balancer
Контейнер с nginx, выполняющий балансировку запрсов с клиентов на указанные адреса.

## Установка
1. Прописать путь к nginx.conf и смонтировать volumes
```
volumes:
      - /etc/nginx/nginx.conf:/etc/nginx/nginx.conf:ro
```
2. Запустить docker-compose
```bash
docker-compose up -d
```
