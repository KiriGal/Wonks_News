# Wonks_News
Тестовый новостной сайт с использованием таких технологий как: docker, nginx, postgres, laravel, react

Для запуска проекта понадобится docker.
Все шаги для успешного запуска проекта:
1) git clone https://github.com/KiriGal/Wonks_News.git
2) cd Wonks_News
3) docker compose up --build
4) docker compose run artisan migrate
5) docker compose run artisan db:seed
6) Наслаждайтесь
