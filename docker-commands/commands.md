docker compose up -d
docker compose down
docker compose up --build
docker compose logs
docker compose logs -f   //follow logs live:

docker compose ps

docker compose exec <service_name> <command> //Execute command in container
