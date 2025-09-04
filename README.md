# Postman API Tests (Reqres)

Учебный проект с API-тестами на Postman + Newman.  
Автоматизация запуска тестов через GitHub Actions.

## Содержание
- Коллекция Postman: **Api tests.postman_collection.json**
- Окружение: **reqres.postman_environment.json**
- CI/CD: `.github/workflows/api-tests.yml`

## Тестируемые сценарии
- 🔑 Auth (login: успешный и негативные кейсы)
- 👤 Users CRUD (get, create, update, delete)
- ❌ Negative (пустая страница, задержка ответа)
- 📐 Validation (JSON Schema)

## Автоотчёт
- При каждом push запускается GitHub Actions.
- Результат сохраняется в **Artifacts** в разделе Actions.