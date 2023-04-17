# Commands
```
docker build -t=docker_project .
docker run -it -d -p 8080:80 --name=changed_nginx docker_project
curl localhost:8080/
```