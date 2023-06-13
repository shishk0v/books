
### Запуск сервиса
```sh
docker-compose build
docker-compose up
```

### Запуск сервиса для отправки тестовых запросов
Передать запрос можно, например через Evans (https://github.com/ktr0731/evans)
```sh
evans ./books/api/proto/books.proto -p 8080
```