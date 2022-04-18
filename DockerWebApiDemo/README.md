docker build -t docker-webapi-demo -f DockerWebApiDemo/Dockerfile .

docker run -d --name docker-webapi-demo-run -p 9002:80 docker-webapi-demo