```
docker build -t docker-webapi-demo -f DockerWebApiDemo/Dockerfile .

docker run -d --name docker-webapi-demo-run -p 9002:80 -e ASPNETCORE_ENVIRONMENT=Development docker-webapi-demo
```

http://localhost:9002/swagger/index.html