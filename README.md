<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarollo

### 1. Installation

```bash
$ yarn install
```

### 2.- Running the app

```bash
# development
$ yarn run start

# watch mode (Recomendado)
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

### 3.- Asegurarse de tener instalado Nest CLI

```
npm i -g @nestjs/cli
```

### 4.- Levantar la base de datos
```
docker-compose up -d
```

### 5.- Reconstruir la base de datos con el seed
```
https://localhost:3000/api/v2/seed
```

## Stack usado
* MongoDB
* Nest
* Mongoose