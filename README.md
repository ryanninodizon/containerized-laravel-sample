# Build and up Container images
- docker-compose build
- docker-compose up

# Start and stop docker-compose
- docker-compose stop
- docker-compose up

# Laravel specific commands
- docker exec laravel-docker bash -c "composer create-project laravel/laravel ."
- docker exec laravel-docker bash -c "composer update"
- docker exec laravel-docker bash -c "php artisan migrate"


