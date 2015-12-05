# Hapi REST API with mongo-sails adapter

Same as ["How to create a REST API with Hapi"](http://blog.webkid.io/how-to-create-a-rest-api-with-hapi/) but using mongo-sails

## Installation

```
npm install -g nodemon && npm install
```

## Start Server

```
nodemon
```

## What do you get?

A simple pizza REST API:

```
http://localhost:1337
  GET    /pizza
  GET    /pizza/count
  POST   /pizza
  GET    /pizza/{id}
  POST   /pizza/{id}
  PATCH  /pizza/{id}
  DELETE /pizza/{id}
```

## Thanks @moklik

For first example https://github.com/wbkd/hapi-rest-starter-simple