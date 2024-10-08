# sae5-01 


## Project Summary

### - Cette SAÉ reproduit la problématique professionnelle consistant à créer, en équipe, une application en suivant une démarche itérative ou incrémentale. Vous allez donc réaliser une application en équipe de 5 ou 6, en suivant une méthode de travail agile, en utilisant des technologies et des outils de développement avancés vus ce semestre.

## Set UP

## There is two ways to start the project:
### Either with Docker or with the command lines:

```bash
docker-compose up --build -d
```
This command can take a lot of time 

```bash
docker exec sae5-01-back-api-1 composer db
```
Depending on the operating system the container's name (sae5-01-back-api-1) can differ

The docker is currently in dev version, but there is also a prod version. To use it, you need to change the docker used in docker-compose.yml (put Dockerfile instead of Dockerfile-dev).

### Soit avec la méthode habituelle:
### Install Symfony

```bash
composer install
```
### Get React on the project 
```bash
npm install
```

### Get the database with docker
```bash
docker-compose up
```

### Install database
```bash
composer db
```

### Build front assets with Webpack Encore

```bash
npm run watch
```


### Run Symfony server
```bash
composer start
```

## Use the application
### How to connect to the application

![Home Page](public/Style/home_page.png "Home Page")


### Teacher account :

```
login : user-0000
password : test
```
### Once logged in as a user, you will end up on this page

![Home Page User](public/Style/home_user.png "Home User")



### Admin account :

### Once logged in as an admin, you will end up on this page

```
login : admi-0000
password : test
```

![Home Page User](public/Style/home_admin.png "Home Admin")


## Php.inig config 
### You need to have at least 256MO of memory_limit otherwise the project (Excel part) won't work
#   S A E _ I U T 
 
 
