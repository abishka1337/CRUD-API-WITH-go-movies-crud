Movie API (на Go)
Простой REST API для управления списком фильмов. Реализован на языке Go с использованием библиотеки Gorilla Mux.

Функции
Получение списка всех фильмов (GET /movies)

Получение фильма по ID (GET /movies/{id})

Добавление фильма (POST /movies)

Обновление фильма (PUT /movies/{id})

Удаление фильма (DELETE /movies/{id})

Технологии
Go

Gorilla Mux

JSON

Как запустить
Клонировать репозиторий:

bash
Копировать
Редактировать
git clone https://github.com/yourusername/movie-api.git
cd movie-api
Установить зависимости:

bash
Копировать
Редактировать
go mod tidy
Запустить проект:

bash
Копировать
Редактировать
go run main.go
Сервер будет доступен по адресу: http://localhost:8000

Пример JSON-запроса для создания фильма
json
Копировать
Редактировать
{
  "isbn": "123456",
  "title": "The Matrix",
  "director": {
    "first_name": "Lana",
    "last_name": "Wachowski"
  }
}
