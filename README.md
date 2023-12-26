Установить и настроить webpack-dev-server. Настроить hot module replacement. Сделать возможность запуска на разных окружениях (dev, prod) c разной конфигурацией (например, убрать HMR на проде). Настроить JSON-server и отображать полученные с него данные. Добавить запуск линтера при комите.

Quick start npm i npm i --save-dev ajv development-mode: webpack.config.js

npm run start-dev production-mode: webpack.prod.js

npm run start-prod JSON-server // Если не установлен, то установить: npm install -g json-server

json-server --watch db.json commit with ESLint check and fix

git commit -a -m "commit_message" Page opens at url http://localhost:8081/
