# sakila
## Sakila Github:
[Sakila Github](https://github.com/AlgebraPHP2020/sakila)
https://getcomposer.org/download/
https://laravel.com/docs/7.x

## Sakila Travis CI
https://travis-ci.org/github/AlgebraPHP2020/sakila
<img src="https://travis-ci.org/github/AlgebraPHP2020/sakila.svg?branch=master" alt="build:passed">


## Postrupak instalacije:
Kloniranje repozitorija:
```sh
$ git clone https://github.com/AlgebraPHP2020/sakila.git
```

Kreiranje laravel projekta:
```sh
$ composer create-project --prefer-dist laravel/laravel sakila-tmp
```

Uci u direktorij sakila:
```sh
$ cd sakila/
```

Pokrenuti web server:
```sh
$ php artisan serve
```

## Postavka SAKILA baze podataka:
[Sakila baza](https://dev.mysql.com/doc/index-other.html)
Dohvati sakila bazu:
```sh
$ cd database
$ php -r "copy('https://downloads.mysql.com/docs/sakila-db.zip', 'sakila-db.zip');"
```

Pokreni skripte u Heidisql:
```SQL
$ RUN sakila-schema.sql
$ RUN sakila-data.sql
```


### Todos
 - [ ] Testiranje na TRAVIS CI --> primjer: https://travis-ci.org/github/mrvic/fakultet
 - [ ] Deploy na Heroku
 - [ ] Code check https://styleci.io/
 - [x] Postaviti XAMPP vhost
