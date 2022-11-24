docker pull nginx:latest

docker run --name nginxWeb -p 8080:80 -d nginx

docker exec -it nginxWeb /bin/bash

docker stop nginxWeb

docker rm nginxWeb


