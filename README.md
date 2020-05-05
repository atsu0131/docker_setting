# docker起動

``` bash
$ docker-compose build
$ docker-compose up -d
```

phpコンテナに入ります

```
$ docker-compose exec php bash
 # npm install
```
dbコンテナに入ります
$ docker-compose exec db bash

Laravelプロジェクト作成

```
$ laravel new 
```

上記にプロジェクト名は付けないこと