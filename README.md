laravel-application deployed by docker-compose

- docker-compose run --rm composer create-project --prefer-dist laravel/laravel:^8.0 .
- docker-compose up mysql server php
- docker-compose run --rm artisan migrate