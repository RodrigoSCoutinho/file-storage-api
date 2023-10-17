<h1 align="center">
  File Storage API
</h1>



## Technologies

- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring MVC](https://docs.spring.io/spring-framework/reference/web/webmvc.html)

## Endpoints

- Upload file:
```
curl -X POST -F "file=@path/to/your/file.txt" http://localhost:8081/api/files/upload
```
- Download file:
```
curl -OJL http://localhost:8081/api/files/download/your-file.txt
```
- List uploaded files:
```
curl http://localhost:8081/api/files/list
```