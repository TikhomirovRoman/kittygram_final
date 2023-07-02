![main workflow](https://github.com/TikhomirovRoman/kittygram_final/actions/workflows/main.yml/badge.svg)
#  Kittygram
учебный проект Яндекс.Практикума

## Описание проекта
Социальная сеть любителей котиков.
Позволяет пользователям публиковать фотографии своих котов и делиться впечатлениями об их достижениях
## Инструкция по разворачиванию

Приложение запускается из контейнеров Docker
скачайте файл **`docker-compose.production.yml`**
перед запуском добавьте необходимые переменные окружения в файл **`.env`** в папке с проектом

для запуска проекта выполните
```
sudo docker compose -f docker-compose.production.yml up --build 
```
Локально приложение будет доступно по адресу 
[http://127.0.0.1:9000](http://127.0.0.1:9000)
## Описание переменных окружения
Ниже пример файла **`.env`** c переменными окружения, необходимыми для запуска приложения
```
POSTGRES_DB=kittygram
POSTGRES_USER=kittygram_user
POSTGRES_PASSWORD=kittygram_password
DB_NAME=kittygram
DB_HOST=db
DEBUG=False
SECRET_KEY=django_secret_key_example
```
## Контакты
[https://github.com/TikhomirovRoman](https://github.com/TikhomirovRoman)

tikhomirov.r@yandex.ru
