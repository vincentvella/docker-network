Create Network:
docker network create favorites-net

Start up MongoDB Container:
docker run -d --name mongodb --network favorites-net mongo

Build and Run local docker container exposing port 3000
docker run -d --name favorites -d --rm -p 3000:3000 --network favorites-net favorites