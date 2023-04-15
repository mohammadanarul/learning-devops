docker build -t express-app-no-install:18 .
docker run -p 4000:3000 express-app-no-install:18

docker ps
docker stop 80b7d7dea09f

docker compose up -d --build
docker compose down