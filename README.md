sudo docker run --name gostack_postgres_2020 -e POSTGRES_PASSWORD=docker -p 5430:5432 -d postgres

sudo docker ps

sudo docker ps -a

sudo docker stop <CONTAINER_ID | NAMES>

sudo docker start <CONTAINER_ID | NAMES>

sudo docker start gostack_postgres_2020
