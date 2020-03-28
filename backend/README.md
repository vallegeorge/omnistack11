
npm init -y
npm install express
npm install nodemon -D

--> banco de dados
npm install knex
npm install sqlite3
npx knex init
npm install cors

npx knex migrate:make create_ongs
-CRIAR A migrate
npx knex migrate:latest (executa as migrates)

npx knex migrate:make create_incidents



------
Frontend
npm create-react-app frontend


