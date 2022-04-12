git remote add origin https://github.com/dsdebayan/demo.git
git config --global user.email "dsdebayan@gmail.com"
git add *
git commit -m ""
git branch -M main
git push -u origin main

http://localhost:8000/swagger-ui/index.html
http://localhost:8000/h2-console

spring-boot:build-image -DskipTests

docker login
docker-compose up
docker container ps
docker image ps
docker container kill pid
docker container prune