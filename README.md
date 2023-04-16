# Installation Requirement

## Using Docker
[Docker](https://docs.docker.com/engine/install/ubuntu/)
[Docker Compose](https://docs.docker.com/compose/install/linux/)

## Linux

PHP >= 8.1
MYSQL >= 8
Composer

# Run Application

## Using Docker

1. Edit configuration on docker-compose.yaml (Optional)
2. Run application using docker-compose `docker-compose up`
3. Access application on browser at 'localhost:8000'
4. To stop the application run `docker-compose down`

## Manually

1. Run 'composer install'
2. Set database configuration on .env file, copy it from .env.example
3. Run 'php artisan migrate'
4. Run 'php artisan key:generate'
5. Run 'php artisan storage:link'
6. Run 'php artisan serve --host=0.0.0.0'
