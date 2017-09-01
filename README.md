# rails-docker
rails project starter


```
docker-compose run --rm web rails new . --force --database=mysql --skip-bundle
```

```
docker-compose build
```

```
docker-compose run --rm web rake db:create
```

```
docker-compose up -d
```
```
docker-compose down
```