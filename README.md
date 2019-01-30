# A basic template for django, docker and postgresql


## Run project

Execute:
```
docker-compose up web
```

And visit: 0.0.0.0:8089


## Tests

```
docker-compose run tests
docker-compose run flake8
docker-compose run mypy
```


## Rebuild

```
docker-compose build
```
