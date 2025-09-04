# Postman API Tests 🚀

![CI](https://github.com/niiksolo/postman-api-tests/actions/workflows/api-tests.yml/badge.svg)

Учебный проект для демонстрации API-тестов с использованием **Postman + Newman + GitHub Actions**.

### 🔑 Что сделано
- Коллекция и окружение Postman  
- Тесты на JS (статусы, ошибки, CRUD, негативные кейсы, схема)  
- Запуск через CI/CD (GitHub Actions)  
- Генерация HTML-отчётов и публикация через GitHub Pages  

### 🔗 Отчёты
👉 [Смотреть последний HTML-отчёт](https://niiksolo.github.io/postman-api-tests/)
⚠️ Время на странице может отличаться от локального, т.к. используется **UTC**.

### 📂 Структура проекта
- `Api tests.postman_collection.json` — коллекция запросов  
- `reqres.postman_environment.json` — окружение  
- `.github/workflows/api-tests.yml` — CI pipeline  
- `report/` — HTML-отчёт (публикуется в Pages)