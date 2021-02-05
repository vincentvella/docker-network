Start up MongoDB Container:
docker run -d --name mongodb mongo

Pull IP Address:
docker inspect mongodb

Build and Run local docker container exposing port 3000