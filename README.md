# DockerLaravel
A repository containing a Docker-ready project

# Contains
1. nginx
2. pgsql
3. php + laravel 11
4. rabbit mq
5. redis
6. cron

# Pre-installed:
1. tymon/jwt-auth
2. zircote/swagger-php
3. vladimir-yuldashev/laravel-queue-rabbitmq
4. predis/predis

# Run:
1. cd backend
2. make get-env
3. sudo make up
4. sudo make first-run

# Tests
1. sudo make test

# Inside php container
1. sudo docker exec -ti backend-service-php-1 /bin/bash

# Swagger
    ./vendor/bin/openapi app -o openapi.yaml
