# Plan-de-formation-nodejs

Plan de formation Nodejs

---

## Pré-requis :

- javascript
- git / github
- node / npm
- es6
- anglais

---

## Jour 1

### Backend developpement vocabulaire :
- routing
- logging
- Authentification
- Caching
- session
- validation
- templates
- api
- orm
- proxy

### Les frameworks & libraires :
- expressjs
- hapijs
- Strapi / Koa / waterline
- sail.js / waterline

### Environnement
- ES6 / babel polyfill
- eslint OU hapijs eslint
- .editorconfig

### Hebergement :
- Heroku
- Zeit

### Les avantages de HAPI :
securité, caching, validation des données, configuration, ...

### En pratique
- first server
- server, request, response, error
- Templating back avec handlebar, ejs, jade ou React (Nous testerons nadlebar, ejs et pour finir react)
- Securiser vos routes (404) - Hapi 
- Exercice : Hapi first API route GET (pour servir le json cf. react cours)

## Jour 2

- Environnement : 
  - postman
  - nodemon
  - node-foreman
  - Clean code (eslint-config-hapi) 
- Hapi plugins
- rest API POST / PUT / DELETE
- validation des données (joi)
- caching
- Exercice : Hapi SSR (sur l'exercice cf. react cours)

## Jour 3

- Base de données
- Sql vs Nosql vs Graph
- We will use Posgresql

- What is an ORM
- Mongoose VS Sequelize VS ... Waterline ... Objection.js
- We will use Sequelize
- separation of concern -> create controller

- Modelisation de BDD : 1->1, 1->n, n->n

- exercice model + controller + routing

## Jour 4


- Authentification : les différentes stratégies (Bearer token, Json Web Token, ...)
- We will use authentification for creation, update and delete et le back-office

- exercice : creation de compte + authentification + creation de commande user/produit (review des competences acquises)

## Jour 5
- Mise en place Repo Github
- Mise en place server Heroku
- Mise en place CDN Amazon S3

- Prise de brief Google map + Photo upload
- Projet Google map + Photo upload avec React / Hapi
- Heroku config (hook github, posgresql, ENV)


## Jour 6

- Projet Google map + Photo upload
- Graphql avec Apollo / Hapijs

## Jour 7

- Projet Google map + Photo upload

- Socket.io
- chat ou jeux temps reel

## Jour 8

- Presentation du projet Google map + Photo upload
