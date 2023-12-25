# Функция *init*

## Назначение функции

Инициализация редактора с передачей версии платформы и имени пользователя

## Параметры функции

* **version** - *string*, версия платформы. Например, 8.3.18.1616
* **user** - *string*, имя пользователя. Используется для установки автора замечаний в режиме Code Review. Необязательный параметр

## Пример вызова

```javascript
init("8.3.18.1616", "Иванов И.И");
```