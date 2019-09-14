# angular-meat-app
This project study the courses Angular 6

Meat - Angular Application
Este respositório contém a implementação da aplicação feita no curso de Angular. O bundle para começar o seu projeto está aqui.

1. Passos para começar
Instalando as Dependências
npm install

Inicializando o Servidor
ng serve ou npm start

2. Iniciando o Backend
Compilando o backend
cd backend
tsc -w
Instalando o nodemon
npm install -g nodemon

Iniciando o serviço (em outra aba de terminal - raiz da aplicação)
nodemon --watch backend backend/dist/server.js

Goodies
Expressões regulares usadas na validação de formulários

Email Regex
/^(([^<>()\[\]\.,;:\s@\"]+(\.[^<>()\[\]\.,;:\s@\"]+)*)|(\".+\"))@(([^<>()[\]\.,;:\s@\"]+\.)+[^<>()[\]\.,;:\s@\"]{2,})$/i

Number Regex
/^[0-9]*$/


