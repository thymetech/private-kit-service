# Private Kit Service
![Build and Tests](https://github.com/imanzano/private-kit-service/workflows/Build%20and%20Tests/badge.svg)(https://github.com/imanzano/private-kit-service/actions?query=workflow%3A%22Build+and+Tests%22)
![Docker Image CI](https://github.com/imanzano/private-kit-service/workflows/Docker%20Image%20CI/badge.svg)(https://github.com/imanzano/private-kit-service/actions?query=workflow%3A%22Docker+Image+CI%22)

An `mvn` wrapper is bundled.

## To run server
```
./mvnw spring-boot:run
```

## To query local endpoint
```
curl localhost:8080
```

## Docker instructions

### Build Dockerfile
```
docker build -t privatekit/self-reporting-server .
```

### Run container
```
docker run -p 8080:8080 privatekit/self-reporting-server
```


