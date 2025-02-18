# Development docker compose

## Docker compose

### To Run
```
docker compose up -d
```

### To Stop
```
docker compose down
```

## Endpoints 

### Get Book
```
curl 'http://localhost:8080/api/books'
```

### Get book by ISBN
```
curl 'http://localhost:8080/api/books/13-3-16-148410-0'
```

### Create Book
```
curl -X 'POST' \
  'http://localhost:8080/api/books' \
  -H 'accept: */*' \
  -H 'Content-Type: application/x-www-form-urlencoded' \
  -d 'title=string&author=string&year=2004&genre=string'
```
