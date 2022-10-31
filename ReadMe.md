### Swagger API доступне за посиланням 
https://backlab1.herokuapp.com/swagger-ui/index.html


### Вимоги до проетку
- JDK 8 or higher
- Spring Boot (v.2.7.4)
- Docker

### Інстуркція до Docker
- Збілдити image з Dockerfile
```
docker build -t <image name> <path to Dockerfile>
```
- Запустити програму з директорії Dockerfile
```
docker run -p<your port>:8080 <image name>
```

