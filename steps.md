## Крок 1

1. npm init -y
2. В корені проекту створи файл index.js
3. npm install nodemon --save-dev
4. "start": "node index"
5. "dev": "nodemon index"

## Крок 2

1. Створив папку db
2. Додав файл contats.json
3. У корені проекту створив файл contacts.js.
4. Зробив імпорт модулів fs i path
5. Створив зміну contactsPath і записав у неї шлях до файлу contacts.json
6. Додав функції для роботи з колекціє даних.
7. Зробив експорт створених функцій через module.exports

## Крок 3

Зроби імпорт модуля contacts.js в файлі index.js та перевір працездатність функції для роботи з контактами.

## Крок 4

1. npm install yargs
2. npm install commander

# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"

# Отримуємо контакт по id

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6

# Додаємо контакт

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22

# Видаляємо контакт

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
